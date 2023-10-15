<script>
    import "../../app.css"; 
    import Sidebar from '../sidebar.svelte';

</script>

<svelte:head>
    <title>Dashboard</title>
</svelte:head>

<div class="w-full min-h-screen bg-[#FAFAFB] flex flex-row">
    <Sidebar />

    <section class="flex-1 ml-5 mr-5">
        <div class="flex justify-between p-3.5">
            <div class="text-left">
                <h1 class="text-2xl font-bold">Customer List</h1>
            </div>
    
            <button class="bg-blue-500 hover:bg-blue-700  font-semibold py-2 px-4 rounded-lg flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 10 10" fill="none">
                    <path d="M9.49994 4.49999H5.50001V0.499968C5.50001 0.224029 5.27599 0 4.99995 0C4.72402 0 4.49999 0.224029 4.49999 0.499968V4.49999H0.499968C0.224029 4.49999 0 4.72402 0 4.99995C0 5.27599 0.224029 5.50001 0.499968 5.50001H4.49999V9.49994C4.49999 9.77597 4.72402 10 4.99995 10C5.27599 10 5.50001 9.77597 5.50001 9.49994V5.50001H9.49994C9.77597 5.50001 10 5.27599 10 4.99995C10 4.72402 9.77597 4.49999 9.49994 4.49999Z" fill="white"/>
                  </svg>
                <span class="ml-2 text-white">Add Customer</span>
              </button>
        </div>
        <div>
            <div class=" rounded-lg ">
                <table class="w-full divide-y divide-gray-200">
                    <thead>
                        <tr>
                            <th class="py-3 px-2 text-left relative text-xs border-b ">
                                Name
                            </th>
                            <th class="py-3 px-2 text-left relative text-xs border-b ">
                                Email
                            </th>
                            <th class="py-3 px-2 text-left relative text-xs border-b ">
                                Phone Number
                            </th>
                            <th class="py-3 px-2 text-left relative text-xs border-b ">
                                Gender
                            </th>
                            <th class="py-3 px-2 text-left relative text-xs border-b">
                                Total Amount
                            </th>
                            <th class="py-3 px-2 text-left relative text-xs border-b">
                                
                            </th>
                        </tr>
                    </thead>
                    <tbody class=" text-xs">

                
                        <tr class="bg-white shadow-xl rounded-lg">
                            <td class="py-4 px-6">
                                <div class="flex items-center">
                                    <img src="../profile.png" class="w-7 h-7 object-cover rounded-full" alt="HP MAHAL CUY">
                                    <span class="ml-2">Diffananda Okta Rosifin</span>
                                </div>
                            </td>
                            <td class="py-4 px-6 ">diffaar@gmail.com</td>
                            <td class="py-4 px-6 ">081234443322</td>
                            <td class="py-4 px-6 ">P</td>
                            <td class="py-4 px-6 ">$1.230</td>
                            <td class="py-4 px-6 justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="4" viewBox="0 0 14 4" fill="none">
                                    <path d="M13.4874 1.01257C12.804 0.329152 11.696 0.329152 11.0126 1.01257C10.3291 1.69598 10.3291 2.80402 11.0126 3.48744C11.696 4.17085 12.804 4.17085 13.4874 3.48744C14.1709 2.80405 14.1709 1.69601 13.4874 1.01257Z" fill="#605BFF"/>
                                    <path d="M8.23744 1.01257C7.55402 0.329152 6.44598 0.329152 5.76257 1.01257C5.07915 1.69598 5.07915 2.80402 5.76257 3.48744C6.44598 4.17085 7.55402 4.17085 8.23744 3.48744C8.92085 2.80405 8.92085 1.69601 8.23744 1.01257Z" fill="#605BFF"/>
                                    <path d="M2.98744 1.01257C2.30402 0.329152 1.19598 0.329152 0.512564 1.01257C-0.170852 1.69598 -0.170852 2.80402 0.512564 3.48744C1.19598 4.17085 2.30402 4.17085 2.98744 3.48744C3.67085 2.80405 3.67085 1.69601 2.98744 1.01257Z" fill="#605BFF"/>
                                </svg>
                            </td>
                        </tr>
                        
                        <tr class="bg-white shadow-xl rounded-lg">
                            <td class="py-4 px-6">
                                <div class="flex items-center">
                                    <img src="../profile.png" class="w-7 h-7 object-cover rounded-full" alt="HP MAHAL CUY">
                                    <span class="ml-2">Aslam Thariq Akbar Akrami</span>
                                </div>
                            </td>
                            <td class="py-4 px-6 ">aslamthariq01@gmail.com</td>
                            <td class="py-4 px-6 ">08123456789</td>
                            <td class="py-4 px-6 ">L</td>
                            <td class="py-4 px-6 ">$1.740</td>
                            <td class="py-4 px-6 justify-center items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="4" viewBox="0 0 14 4" fill="none">
                                    <path d="M13.4874 1.01257C12.804 0.329152 11.696 0.329152 11.0126 1.01257C10.3291 1.69598 10.3291 2.80402 11.0126 3.48744C11.696 4.17085 12.804 4.17085 13.4874 3.48744C14.1709 2.80405 14.1709 1.69601 13.4874 1.01257Z" fill="#605BFF"/>
                                    <path d="M8.23744 1.01257C7.55402 0.329152 6.44598 0.329152 5.76257 1.01257C5.07915 1.69598 5.07915 2.80402 5.76257 3.48744C6.44598 4.17085 7.55402 4.17085 8.23744 3.48744C8.92085 2.80405 8.92085 1.69601 8.23744 1.01257Z" fill="#605BFF"/>
                                    <path d="M2.98744 1.01257C2.30402 0.329152 1.19598 0.329152 0.512564 1.01257C-0.170852 1.69598 -0.170852 2.80402 0.512564 3.48744C1.19598 4.17085 2.30402 4.17085 2.98744 3.48744C3.67085 2.80405 3.67085 1.69601 2.98744 1.01257Z" fill="#605BFF"/>
                                </svg>
                            </td>
                        </tr>
                        
                    </tbody>
                </table>
        </div>
    </section>
    <section class="w-96 flex flex-col items-center p-4 bg-white ">
        <div class="mb-4 mt-28">
            <img src="../profile.png" class="w-20 h-20 object-cover rounded-full" alt="profil">
        </div>
        <h2 class="text-xl font-semibold mb-2">
            Aslam Thariq Akbar Akrami
        </h2>
        <p class="text-gray-500 mb-2" >
            Front-end Developer
        </p>
    
        
    
        <div class="text-left ">
            <div class="flex-items-start font-semibold mb-5 mt-10 ml-0">
                Contact Info
            </div>
            <div class="flex items-start mb-2 "  >
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="15" viewBox="0 0 16 15" fill="none">
                    <g opacity="0.3">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M11.9512 0C13.024 0 14.056 0.441667 14.8152 1.23417C15.5752 2.025 16 3.09167 16 4.20833V10.7917C16 13.1167 14.184 15 11.9512 15H4.048C1.8152 15 0 13.1167 0 10.7917V4.20833C0 1.88333 1.8072 0 4.048 0H11.9512ZM13.224 5.44987L13.288 5.3832C13.4792 5.14153 13.4792 4.79153 13.2792 4.54987C13.168 4.4257 13.0152 4.34987 12.856 4.3332C12.688 4.32403 12.528 4.3832 12.4072 4.49987L8.79999 7.49987C8.33599 7.9007 7.67119 7.9007 7.19999 7.49987L3.59999 4.49987C3.35119 4.3082 3.00719 4.3332 2.79999 4.5582C2.58399 4.7832 2.55999 5.14153 2.74319 5.39153L2.84799 5.49987L6.48799 8.4582C6.93599 8.82487 7.47919 9.02487 8.04799 9.02487C8.61519 9.02487 9.16799 8.82487 9.61519 8.4582L13.224 5.44987Z" fill="#030229"/>
                    </g>
                </svg>
                <span class="ml-4 text-gray-600">aslamthariq01@gmail.com</span>
            </div>
            <div class="flex items-start mb-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16" fill="none">
                    <g opacity="0.3">
                        <path d="M12.9335 9.90336C12.3961 9.78777 11.971 10.0373 11.5946 10.2551C11.2091 10.4797 10.4761 11.0743 10.056 10.9221C7.90487 10.0364 5.88171 8.15363 5.00591 5.9939C4.85155 5.56478 5.4434 4.82713 5.66626 4.4371C5.88253 4.05954 6.12686 3.63042 6.01543 3.08904C5.91472 2.60254 4.61217 0.94511 4.15158 0.491875C3.84781 0.19249 3.53662 0.0278285 3.21718 0.00121652C2.01616 -0.0503442 0.674813 1.5522 0.439562 1.93557C-0.149804 2.75306 -0.146502 3.84082 0.449467 5.15978C1.88574 8.7025 7.31798 14.049 10.874 15.5393C11.5302 15.8462 12.1303 16 12.6693 16C13.1968 16 13.6665 15.8528 14.0701 15.5609C14.3747 15.3854 16.0429 13.9775 15.9992 12.7442C15.9727 12.4298 15.8085 12.1155 15.513 11.8111C15.0631 11.3462 13.4163 10.0048 12.9335 9.90336Z" fill="#030229"/>
                    </g>
                </svg>
                <span class="ml-4  text-gray-600">08123456789</span>
                
            </div>
            <div class="flex items-start" >
                <svg xmlns="http://www.w3.org/2000/svg" width="14" height="17" viewBox="0 0 14 17" fill="none">
                    <g opacity="0.3">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M0 7.07009C0 3.16021 3.16555 0 6.9946 0C10.8344 0 14 3.16021 14 7.07009C14 9.04034 13.3058 10.8695 12.1631 12.4198C10.9025 14.13 9.34883 15.62 7.59998 16.7896C7.19972 17.0599 6.83848 17.0803 6.39919 16.7896C4.64037 15.62 3.08666 14.13 1.83688 12.4198C0.693398 10.8695 0 9.04034 0 7.07009ZM4.68945 7.29019C4.68945 8.6 5.72498 9.63017 6.99469 9.63017C8.26523 9.63017 9.31072 8.6 9.31072 7.29019C9.31072 5.99058 8.26523 4.91026 6.99469 4.91026C5.72498 4.91026 4.68945 5.99058 4.68945 7.29019Z" fill="#030229"/>
                    </g>
                </svg>
                <span class="ml-4  text-gray-600">Jl. Contoh No. 123, Kota Sana sini Provinsi sana</span>
                
            </div>
        </div>
    </section>
    
    
    
    
</div>