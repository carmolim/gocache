<template>
    <main class="container">

        <div class="my-4 pb-3 border-bottom">

            <div class="row align-items-center">

                <div class="col-md-4">
                    <h1 class="h mb-0 lh-1">{{pageTitle}}</h1>
                    <small class="d-block mb-3 mb-md-0">O front foi criado utilizando VUE 3 e Bootstrap</small>
                </div>

                
            </div>

        </div>

    </main>

</template>

<script>

export default {
    name: 'About',
    data() {
        return{
            pageTitle: 'About'
        }
    }
}

</script>