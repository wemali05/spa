<template>
    <div>
         <h3>Some User Details</h3>
         <p>User Loaded has ID: {{ $route.params.id }}</p>
         <router-link
              tag="button"
              class="btn btn-primary"
              :to="{ name: 'userEdit', params: { id: $route.params.id }, query: { locale: 'en', q: 100}}" >Edit user</router-link>
    </div>
</template>