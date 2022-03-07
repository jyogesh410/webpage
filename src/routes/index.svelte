<script >
    import Dropdown from "../components/Dropdown.svelte";
    
    </script>
    <div class="flex">
<aside class="w-60">
    <div class=" py-4 px-3  ">
       <ul class="text-xl" >
          <li>
             <a href="#" class="flex  p-2  text-gray-500 hover:text-gray-900  rounded-lg hover:bg-indigo-100 ">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                   <path d="M10.707 2.293a1 1 0 00-1.414 0l-7 7a1 1 0 001.414 1.414L4 10.414V17a1 1 0 001 1h2a1 1 0 001-1v-2a1 1 0 011-1h2a1 1 0 011 1v2a1 1 0 001 1h2a1 1 0 001-1v-6.586l.293.293a1 1 0 001.414-1.414l-7-7z" />
                 </svg>
                <span class="ml-3">Home</span>
             </a>
          </li>
          <li>
             <a href="#" class="flex  p-2  text-gray-500 hover:text-gray-900 rounded-lg  hover:bg-indigo-100 ">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                   <path fill-rule="evenodd" d="M6 2a2 2 0 00-2 2v12a2 2 0 002 2h8a2 2 0 002-2V7.414A2 2 0 0015.414 6L12 2.586A2 2 0 0010.586 2H6zm2 10a1 1 0 10-2 0v3a1 1 0 102 0v-3zm2-3a1 1 0 011 1v5a1 1 0 11-2 0v-5a1 1 0 011-1zm4-1a1 1 0 10-2 0v7a1 1 0 102 0V8z" clip-rule="evenodd" />
                 </svg>
                <span class=" ml-3 ">Dashboard</span>
             </a>
          </li>
          <li>
             <a href="#" class="flex  p-2  text-gray-500 hover:text-gray-900 rounded-lg  hover:bg-indigo-100 ">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                   <path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z" clip-rule="evenodd" />
                 </svg>
                <span class=" ml-3">About</span>
             </a>
          </li>
          <li>
             <a href="#" class="flex  p-2   text-gray-500 hover:text-gray-900 rounded-lg  hover:bg-indigo-100 ">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mt-1.5" viewBox="0 0 20 20" fill="currentColor">
                   <path d="M2 3a1 1 0 011-1h2.153a1 1 0 01.986.836l.74 4.435a1 1 0 01-.54 1.06l-1.548.773a11.037 11.037 0 006.105 6.105l.774-1.548a1 1 0 011.059-.54l4.435.74a1 1 0 01.836.986V17a1 1 0 01-1 1h-2C7.82 18 2 12.18 2 5V3z" />
                 </svg>
                <span class=" ml-3 ">Contact</span>
             </a>
          </li>
       
       </ul>
    </div>
 </aside>

 <div class="container flex px-5 py-5 " >
    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 ml-64" viewBox="0 0 20 20" fill="currentColor">
        <path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z" />
        <path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm3 4a1 1 0 000 2h.01a1 1 0 100-2H7zm3 0a1 1 0 000 2h3a1 1 0 100-2h-3zm-3 4a1 1 0 100 2h.01a1 1 0 100-2H7zm3 0a1 1 0 100 2h3a1 1 0 100-2h-3z" clip-rule="evenodd" />
      </svg>
    <h1 class="px-2 ml-40">CASES</h1>
    </div>
    </div>
    <div class="flex items-center justify-center">
        <div class="flex border-2 rounded">
            <input type="text" class="px-4 py-2 w-80" placeholder="Search...">
            <button class="flex items-center justify-center px-4 border-l">
                <svg class="w-6 h-6 text-gray-600" fill="currentColor" xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24">
                    <path
                        d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z" />
                </svg>
            </button>
        </div>
    </div>
    
    <div class="flex items-center justify-center py-10">
      <span>
          <Dropdown name="CASES" list1="CRC prnding" list2="Not activated" list3="Closed" list4="Opened"></Dropdown>
      </span>
      <span>
        <Dropdown name="COUNTRY" list1="India" list2="Canada" list3="America" list4="Russia"></Dropdown>
    </span>
    <span>
        <Dropdown name="TYPE" list1="Direct" list2="Client" list3="Vendor" list4=""></Dropdown>
    </span>
    <span>
        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-10 py-3 text-center mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Create</button>         
    </span>
    </div>
      
    <div class="container flex justify-center mx-auto px-1 py-10">
        <div class="flex flex-col">
            <div class="w-full">
                <div class="border-b border-gray-200 shadow">
                    <table>
                        <thead class="bg-gray-50">
                            <tr>
                                <th class="px-6 py-2 text-xs text-gray-500">
                                    ID
                                </th>
                                <th class="px-6 py-2 text-xs text-gray-500">
                                First Name
                                </th>
                                <th class="px-6 py-2 text-xs text-gray-500">
                                    Last Name
                                </th>
                                <th class="px-6 py-2 text-xs text-gray-500">
                                    Email
                                </th>
                                
                            </tr>
                        </thead>
                        <tbody class="bg-white">
                            <tr class="whitespace-nowrap">
                                <td class="px-6 py-4 text-sm text-gray-500">
                                    1
                                </td>
                                <td class="px-6 py-4">
                                    <div class="text-sm text-gray-900">
                                        John
                                    </div>
                                </td>
                                <td class="px-6 py-4 text-sm text-gray-500">
                                    doe
                                </td>
                                <td class="px-6 py-4">
                                    <div class="text-sm text-gray-500">jhondoe@example.com</div>
                                </td>
                               
                                
                            </tr>
    
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>  
    
