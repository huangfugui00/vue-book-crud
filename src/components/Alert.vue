<template>
    <div>
        <b-alert variant="success" show>
            {{message}}
        </b-alert>
        <hr>
    </div>
</template>

<script>
export default {
    name: "Alert",
    props:['message'],
}
</script>