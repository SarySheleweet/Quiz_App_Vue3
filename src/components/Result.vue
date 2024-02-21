<script setup>
import {defineProps} from 'vue'
import {RouterLink} from 'vue-router'

const {numberofCorrectAnswers, quizQuestionLength } = defineProps(["numberofCorrectAnswers", "quizQuestionLength"])

</script>

<template>
    <div class="results">
        <p>Your Results ...</p>
        <h1> {{numberofCorrectAnswers}}</h1>
        <RouterLink />Go Back
    </div>
</template>

<style scoped>
.results {
    text-align: center;
    padding: 100px 0;
}

p {
    font-size: 25px;
}
h1 {
    font-size: 25px;
}
</style>