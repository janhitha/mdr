<template>
  <Layout>
    <div>
      <!-- title -->
			<div class=" w-full  flex  flex-row  flex-wrap  bg-gray-600  p-10  py-20  justify-center" 
     style="background-repeat: no-repeat; background-attachment: fixed; background-blend-mode: multiply;background-position: center;background-image: url('images/call-us.png');">
     <div class=" w-full  text-center">
       <div class=" text-3xl  text-center text-white  antialiased">Contact Us</div>
     </div>
   </div> 
			<!-- /title -->
  <div class="container mx-auto ">
      <div class="w-full bg-white">
<div id="content-wrapper"> 
			<div class="container max-w-4xl mx-auto pb-10 px-12 md:px-0 mt-8">

				<div class="flex flex-wrap justify-start items-start -mx-4 bg-gray-100">
					<div class="w-full md:w-1/2 p-4">
						<p class="font-bold mb-1 text-gray-900 font-sans">
							MDR RIPL (Head Office)
						</p>
						<p class="text-sm mb-2 text-gray-900">
							Plot No-235,Sai Sadan,1st Floor,Khanampet,Madhapur(po),<br />
							Hyderabad,<br />
							500081
						</p>
						<p class="text-black font-bold">(040) 424 08591</p>
						<br />
					</div>
		<!-- Container -->
					<div class="w-full lg:w-7/12 bg-white p-5 rounded-lg lg:rounded-l-none">
						<h3 class="pt-4 text-2xl text-center">Contact Us</h3>
						<form class="px-8 pt-6 pb-8 mb-4 bg-white rounded">
							<div class="mb-4 md:flex md:justify-between">
								<div class="mb-4 md:mr-2 md:mb-0">
									<label class="block mb-2 text-sm font-bold text-gray-700" for="firstName">First Name</label>
									<input
										class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
										id="firstName"
										type="text"
										placeholder="First Name"
									/>
								</div>
								<div class="md:ml-2">
									<label class="block mb-2 text-sm font-bold text-gray-700" for="lastName">Last Name</label>
									<input
										class="w-full px-3 py-2 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
										id="lastName"
										type="text"
										placeholder="Last Name"
									/>
								</div>
							</div>
							<div class="mb-4">
								<label class="block mb-2 text-sm font-bold text-gray-700" for="email">Email</label>
								<input
									class="w-full px-3 py-2 mb-3 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
									id="email"
									type="email"
									placeholder="Email"
								/>
							</div>
							<div class="mb-4">
								<label class="block mb-2 text-sm font-bold text-gray-700" for="email">Message</label>
								<textarea
									class="w-full px-3 py-2 mb-3 text-sm leading-tight text-gray-700 border rounded shadow appearance-none focus:outline-none focus:shadow-outline"
									id="notes"
									type="text"
									placeholder="Message"
								/>
							</div>
							<div class="mb-6 text-center">
								<button
									class="w-full px-4 py-2 font-bold text-white bg-blue-500 rounded-full hover:bg-blue-700 focus:outline-none focus:shadow-outline"
									type="button">Submit</button>
							</div>
							<hr class="mb-6 border-t" />
						</form>
					</div>
				</div>
			</div>
		</div>
	</div>		 
  </div>
</div>
  </Layout>  
</template>