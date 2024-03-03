<link
	href="https://fonts.googleapis.com/css?family=Material+Icons|Material+Icons+Outlined|Material+Icons+Two+Tone|Material+Icons+Round|Material+Icons+Sharp"
	rel="stylesheet">
	<link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet">
<div class="flex items-center justify-center text-xl text-blue-500 py-3 ">
    <h2>Recent Orders</h2>
</div> 
<div class="flex items-center justify-center mx-auto px-6 max-w-6xl">
     
	<div class="col-span-12">
		<div class="overflow-auto lg:overflow-visible ">
			<table class="table text-gray-400 border-separate space-y-6 text-sm">
				<thead class="bg-gray-100 text-gray-950">
					<tr>
						<th class="p-3 text-left">Name</th>
						<th class="p-3 text-left">Category</th>
						<th class="p-3 text-left">Price</th>
						<th class="p-3 text-left">Status</th>
						<th class="p-3 text-left">Action</th>
					</tr>
				</thead>
				<tbody>
					<tr class="bg-gray-100">
						<td class="p-3">
							<div class="flex align-items-center">
								
								<div class="ml-3">
									<div class="text-gray-900">Asadur Rahman</div>
									<div class="text-gray-400">23/A, Basundhara Residnetial, Dhaka</div>
								</div>
							</div>
						</td>
						<td class="p-3">
							Technology
						</td>
						<td class="p-3 font-bold">
							200.00$
						</td>
						<td class="p-3">
							<span class="bg-green-400 text-gray-50 rounded-md px-2">available</span>
						</td>
						<td class="p-3">

							<a href="#" class="text-gray-400 hover:text-gray-100  mx-2">
								<i class="material-icons-outlined text-base">edit</i>
							</a>

						</td>
					</tr>
					<tr class="bg-gray-100">
						<td class="p-3">
							<div class="flex align-items-center">
								
								<div class="ml-3">
									<div class="text-gray-900">Jamil Karim</div>
									<div class="text-gray-400">56/A, West Nakhalpara, Satmojil road, Dhaka</div>
								</div>
							</div>
						</td>
						<td class="p-3">
							Technology
						</td>
						<td class="p-3 font-bold">
							200.00$
						</td>
						<td class="p-3">
							<span class="bg-red-400 text-gray-50 rounded-md px-2">no stock</span>
						</td>
						<td class="p-3">
							
							<a href="#" class="text-gray-400 hover:text-gray-100 mx-2">
								<i class="material-icons-outlined text-base">edit</i>
							</a>
						
						</td>
					</tr>
					<tr class="bg-gray-100">
						<td class="p-3">
							<div class="flex align-items-center">
								
								<div class="ml-3">
									<div class="text-gray-900">Asadur Rahman</div>
									<div class="text-gray-400">23/A, Basundhara Residnetial, Dhaka</div>
								</div>
							</div>
						</td>
						<td class="p-3">
							Technology
						</td>
						<td class="p-3 font-bold">
							200.00$
						</td>
						<td class="p-3">
							<span class="bg-yellow-400 text-gray-50  rounded-md px-2">start sale</span>
						</td>
						<td class="p-3">
				
							<a href="#" class="text-gray-400 hover:text-gray-100 mx-2">
								<i class="material-icons-outlined text-base">edit</i>
							</a>
						
						</td>
					</tr>
				</tbody>
			</table>
		</div>
	</div>
</div>

<style>
	.table {
		border-spacing: 0 10px;
	}

	i {
		font-size: 1rem !important;
	}

	.table tr {
		border-radius: 20px;
	}

	tr td:nth-child(n+5),
	tr th:nth-child(n+5) {
		border-radius: 0 .625rem .625rem 0;
	}

	tr td:nth-child(1),
	tr th:nth-child(1) {
		border-radius: .625rem 0 0 .625rem;
	}
</style>