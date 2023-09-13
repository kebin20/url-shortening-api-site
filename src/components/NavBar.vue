<template>
    <nav class="nav-links">
      <ul>
      <li>Features</li>
      <li>Pricing</li>
      <li>Resources</li>
    </ul>

    <div class="nav-buttons">
      <a class="login-btn" href="/login">Login</a>
      <a class="signup-btn" href="/signup">Sign Up</a>
    </div>
    </nav>
</template>

<style scoped>

.nav-links {
    display: flex;
    flex-direction: column;
}

.nav-buttons > a{
    padding: 1em;
    text-decoration: none;
}

.signup-btn {
padding: 0.1em 1em;
border-radius: 28px;
background: #2BD0D0;
color: white;
}

</style>