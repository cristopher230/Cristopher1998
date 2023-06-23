<script>
    import "/src/input.css"
</script>
<div class="flex h-full">
    <div class="flex flex-col w-64 ">
        <div class="mx-10 mt-4">
            <!-- svelte-ignore a11y-missing-attribute -->
            <img src="logo.png">
        </div>
    </div>
    
<!-- Side navigation content -->
<div class="sidenav fixed left-0 top-0 h-full w-64 flex flex-col bg-white">
    <div class="flex items-center justify-between"> 
       <!-- svelte-ignore a11y-missing-attribute -->
       <img src="/logo.png"class="h-8 ml-3 w-52 mt-5">
    </div>
     <div class="p-2.5 mt-10  mx-2.5 mr-2 flex items-center rounded-full px-6 duration-300 cursor-pointer hover:bg-blue-500">
        <i class="fa fa-home"></i>
        <span class="text-[20px] ml-4 color-black w-10 font-medium ">Dashboard</span>
     </div>
     <div class="p-2.5 mt-2 mx-2.5 mr-2 flex items-center rounded-full px-6 duration-300 cursor-pointer hover:bg-blue-500">
        <i class="fa fa-file-o"></i>
        <span class="text-[20px] font-size-10px ml-4 font-medium ">Forms</span>
     </div>
     <div class="p-2.5 mt-2 mx-2.5 mr-8 flex items-center rounded-full px-6  bg-blue-500">
        <i class="fa fa-users"></i>
        <span class="text-[20px] ml-4 font-medium ">Respondents</span>
     </div>
    </div> 
    <div class="flex-1 flex flex-col">
        <header class="bg-blue-100 text-black font-semibold p-4 flex justify-between items-center">
          <!-- Header content -->
          <div class="flex items-center">
            <!-- svelte-ignore a11y-missing-attribute -->
            <img src="university.png" class="h-10 w-10 mr-2">
            <span class="text-2xl">University of Tokyo</span>
          </div>
            <div class="bg-white rounded-full h-10 w-10 absolute top-4 right-0 mr-20 flex items-center justify-center cursor-pointer hover:bg-blue-500">
                <i class="fas fa-bell text-black"></i>
            </div>
            <span class="badge bg-blue-500 text-white rounded-full h-10 w-10 flex text-2xl items-center justify-center">Y</span>
        </header>
        <div class="flex-1 flex">
          <div class="flex-1 bg-blue-100 p-3">
            <!-- Dashboard content -->
            <div class=" bg-white m-5 h-screen p-5">
                <h1 class="text-3xl p-5 font-semibold">Respondents</h1>
                <div class="  bg-slate-200 w-100 h-0.5 mt-2 m-5"></div>
               
               
                <div class="grid grid-cols-3 gap-10  mt-10 h-4/5">
                    <div class=" text-lg border-solid border-2 rounded-md font-semibold ml-5">
                        <div class=" ml-5 mt-5 text-3xl">Untitled form
                            <div class="flex justify-between mt-5">
                                <p1 class="font-semibold ml-4 mt-8 text-lg border-solid border-2 rounded px-6 bg-blue-500">responses</p1>
                               <p1 class="font-semibold ml-4 mt-8 mr-6 text-lg rounded border-solid border-2 px-4 ">nonresponses</p1>
                               
                            </div>
                            <div class="font-semibold ml-24 mt-10 text-lg mr-20 px-2 rounded  border-solid border-2">26 responses</div>
                            <div class="columns-1  border-solid border-2 rounded-md mt-5 h-80 mr-6">
                                <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="ai.jpg" class=" rounded-full w-10 ml-8 mt-3">
                                    <span class="text-lg ml-3 mt-3">Ai Fujikura</span>
                                  </div>             
                                  <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="asahi.png" class=" rounded-full w-10 ml-8 mt-2">
                                    <span class="text-lg ml-3 mt-3">Asahi Bessho</span>
                                  </div> 
                                  <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="chiyo.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                    <span class="text-lg ml-3 mt-3">Chiyo Hada</span>
                                  </div>
                                    <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="daiki.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Daiki Sato</span>
                                      </div>  
                                      <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="emiko.png" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Emiko Takahashi</span>
                                      </div>  
                                      <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="hana.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Hana Nakamura</span>
                                      </div>   
                            </div>
                            
                        </div>
                
                    </div>
                
                    <div class=" text-lg border-solid border-2 rounded-md font-semibold ">
                        <div class=" ml-5 mt-5  text-3xl">Untitled form
                            <div class="flex justify-between mt-5">
                                <p1 class="font-semibold ml-4 mt-8 text-lg rounded px-6 border-solid border-2  bg-blue-500">responses</p1>
                               <p1 class="font-semibold ml-4 mt-8 mr-6 text-lg rounded border-solid border-2 px-6 ">nonresponses</p1>
                            </div>
                            <div class="font-semibold ml-24 mt-10 text-lg rounded mr-24 px-3 border-solid border-2 ">26 responses</div>
                            <div class="columns-1  border-solid border-2 rounded-md mt-5 h-80 mr-6">
                            
                                <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="ai.jpg" class=" rounded-full w-10 ml-8 mt-3">
                                    <span class="text-lg ml-3 mt-3">Ai Fujikura</span>
                                  </div>             
                                  <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="asahi.png" class=" rounded-full w-10 ml-8 mt-2">
                                    <span class="text-lg ml-3 mt-3">Asahi Bessho</span>
                                  </div> 
                                  <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="chiyo.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                    <span class="text-lg ml-3 mt-3">Chiyo Hada</span>
                                  </div>
                                    <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="daiki.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Daiki Sato</span>
                                      </div>  
                                      <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="emiko.png" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Emiko Takahashi</span>
                                      </div>  
                                      <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="hana.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Hana Nakamura</span>
                                      </div>  
                            
                            </div>
                        </div>
                        </div>
                         
                    <div class="text-lg rounded-md border-solid border-2 font-semibold mr-5">
                        <div class=" ml-5 mt-5 text-3xl">Untitled form
                            <div class="flex justify-between mt-5">
                                <p1 class="font-semibold ml-4 mt-8 text-lg rounded px-6 border-solid border-2 bg-blue-500">responses</p1>
                               <p1 class="font-semibold ml-4 mr-6 mt-8 text-lg rounded px-4 border-solid border-2 ">nonresponses</p1>
                            </div>
                            <div class="font-semibold ml-24 mt-10 text-lg rounded mr-20 px-2 border-solid border-2 ">26 responses</div>
                            <div class="columns-1 border-solid border-2 rounded-md mt-5 h-80 mr-6">
                                <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="ai.jpg" class=" rounded-full w-10 ml-8 mt-3">
                                    <span class="text-lg ml-3 mt-3">Ai Fujikura</span>
                                  </div>             
                                  <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="asahi.png" class=" rounded-full w-10 ml-8 mt-2">
                                    <span class="text-lg ml-3 mt-3">Asahi Bessho</span>
                                  </div> 
                                  <div class="flex items-center">
                                    <!-- svelte-ignore a11y-missing-attribute -->
                                    <img src="chiyo.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                    <span class="text-lg ml-3 mt-3">Chiyo Hada</span>
                                  </div>
                                    <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="daiki.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Daiki Sato</span>
                                      </div>  
                                      <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="emiko.png" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Emiko Takahashi</span>
                                      </div>  
                                      <div class="flex items-center">
                                        <!-- svelte-ignore a11y-missing-attribute -->
                                        <img src="hana.jpg" class=" rounded-full w-10 ml-8 mt-2">
                                        <span class="text-lg ml-3 mt-3">Hana Nakamura</span>
                                      </div>   
                            </div>
                        </div>
                    </div>
                
        </div>
                  

            

                
            
            </div>
        </div>
    </div>
</div>
</div>
