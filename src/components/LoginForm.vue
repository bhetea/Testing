<template>
    <div class="centre">
        <form>
            <label>Welcome</label>
            <p>Login/SignUp</p>
            <input type="text" placeholder="Name" v-model="name">
            <input type="email" placeholder="Email" v-model="email">
            <input type="password" placeholder="Password" v-model="password">

            <button>Sign Up</button>

            <p>Name: {{ name }}</p>
            <p>Email: {{ email }}</p>
            <p>Password: {{ password }}</p>
        </form>
    </div>
</template>

<script>
export default {
    data() {
        return {
            name: '',
            email: '',
            password: ''

        }

    }
}
</script>