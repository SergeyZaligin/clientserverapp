
<template>
  <h1>Звёзды: {{ $store.state.stars }}</h1>
</template>

<script>
import axios from 'axios';
 axios
        .get('http://localhost:3000/api/vacations')
        .then(function (response) {
            console.log(response.data);
        })
        .catch(function (error) {
            console.log(error);
        });

</script>
