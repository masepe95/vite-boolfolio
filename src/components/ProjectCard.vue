<script>

export default {

    props: {

        project: Object

    },

    data() {

        return {



        }

    },

    methods: {



    }

}

</script>




<template>
    <div class="card p-5 bg-dark text-white">
        <div class="card-header rounded border-0 mb-4 d-flex justify-content-between align-content-center ">
            <h2 class="m-0 d-flex align-items-center">
                {{ project.title }}
            </h2>
        </div>
        <div class="card-body">
            <p class="">
                {{ project.description }}
            </p>
        </div>
        <div class="card-footer d-flex justify-content-between mt-3 align-items-center border-0 bg-dark">
            <div>
                Created: {{ project.created_at }} <br>
                Last Modified at: {{ project.updated_at }}
            </div>
        </div>
    </div>
</template>




<style scoped></style>