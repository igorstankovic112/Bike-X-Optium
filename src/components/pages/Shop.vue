<template>
    <div class="latest-products" bis_skin_checked="1">
        <div class="container" bis_skin_checked="1">
            <div class="row" bis_skin_checked="1">
                <div class="col-md-12" bis_skin_checked="1">
                    <div class="section-heading" bis_skin_checked="1">
                        <h2>Shopping cart</h2>
                    </div>
                </div>
                <div class="row row-cols-1 row-cols-md-3 g-4" id="row" bis_skin_checked="1">
                    <div class="container-fluid table-wrap" bis_skin_checked="1">
                        <table id="table" class="table table-bordered ">
                            <thead>
                                <tr>
                                    <th scope="col">Item</th>
                                    <th scope="col">Name</th>
                                    <th scope="col">Quantity</th>
                                    <th scope="col">Price</th>
                                </tr>
                            </thead>
                        </table>
                    </div>
                </div>

            </div>
            <div id="emptyCart" bis_skin_checked="1">
                <h2>Your shopping cart is empty!</h2>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "ShopComponent"
}
</script>