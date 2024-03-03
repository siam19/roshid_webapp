<script>
	import Metrics from "./metrics.svelte";
    import OrderTable from "./order-table.svelte";
</script>



<h1 class=" text-blue-600 text-center text-4xl m-4">Roshid</h1>


<!--create a list of all the pages ("New Order" , "Create Product", "Setup Delivery) -->

<ul class="flex justify-center">
    <li class="m-4">
        <a href="/new-order" class="text-blue-600">New Order</a>
    </li>
    <li class="m-4">
        <a href="/create-product" class="text-blue-600">Create Product</a>
    </li>
    <li class="m-4">
        <a href="/setup-delivery" class="text-blue-600">Setup Delivery</a>
    </li>
</ul>

<Metrics/>
<OrderTable/>
```

