<template>
    <div class="question-box-container">
        <b-jumbotron>
            <template v-slot:lead>
                Some question here?
            </template>

            <hr class="my-4">

            <p>
                List of answers
            </p>

            <b-button variant="primary" href="#">Submin</b-button>
            <b-button variant="success" href="#">Next</b-button>
        </b-jumbotron>
    </div>
</template>