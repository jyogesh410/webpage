<script>
  import "../app.css";
</script>
<div class="bg-black flex px-4 py-2 ">
<img class="h-10 ml-4" src="/static/freeze.png" />
<h1 class="text-white ml-6 mt-3 uppercase tracking-widest font-semibold ">Freez</h1>
<div class="container flex mx-auto ml-64">
    <div class="flex border-2 rounded">
        <button class="flex items-center justify-center bg-white px-4 border-r">
            <svg class="w-6 h-6 text-black " fill="currentColor" xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24">
                <path
                    d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z">
                </path>
            </svg>
        </button>
        <input type="text" class=" w-96 px-4 py-2 rounded-lg" placeholder="Search...">
    </div>
</div>
<button class="py-4 px-1 relative border-2 border-transparent text-gray-800 rounded-full hover:text-gray-400 focus:outline-none focus:text-gray-500 transition duration-150 ease-in-out" aria-label="bell">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mb-4 text-white origin-top-right absolute right-60" viewBox="0 0 20 20" fill="currentColor">
        <path d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z" />
      </svg>
    <span class="absolute inset-0 object-right-top -mr-6">
      <div class="inline-flex items-center px-1.5 py-0.5 border-2 origin-top-right absolute right-64 border-white rounded-full text-xs font-semibold leading-4 bg-red-300 text-white">
        6
      </div>
    </span>
  </button>
  
  <img class="h-10 origin-top-right absolute right-40 rounded-full mt-1 border-2 border-gray-200" src="/static/user.jfif" alt="user" />
  <!--button>
  <div class="w-48 bg-white rounded-lg py-2">
      <a href="#" class="block px-4 py-2 text-gray-900">View Profile</a>
      <a href="#" class="block px-4 py-2 text-gray-900">Account Settings</a>

      <a href="#" class="block px-4 py-2 text-gray-900">Signout</a>

  </div>
  </button-->
  <h2 class="text-white mt-2  origin-top-right absolute right-10">Yogeshwaran</h2>

 
</div>

<slot />
