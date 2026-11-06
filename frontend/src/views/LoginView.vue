<template>
  <main>
    <div>
      <!-- Logo -->
      <div>
        <div>
          <span>eco</span>
        </div>
        <div>
          <span>AgriTrack</span>
          <span>v1.0</span>
        </div>
        <p>Crop Progress &amp; Field Management</p>
      </div>
      <!-- Role Selection -->
      <div>
        <span>verified_user</span>
        <p>
          Role is automatically derived from your verified account credentials
          (no manual role selector required).
        </p>
      </div>
      <!-- Login Form -->
      <form action="">
        <!-- Username -->
        <div>
          <label for="email">
            <span>Work Email</span>
            <span>Field or Admin ID</span>
          </label>
          <div>
            <span>mail</span>
            <input
              autocomplete="email"
              type="email"
              placeholder="test@example.com"
              name="email"
              id="email"
              required
            />
          </div>
        </div>
        <!-- Password -->
        <div>
          <div>
            <label for="password">Password</label>
            <a href="#">Forgot password?</a>
          </div>
          <div>
            <span>lock</span>
            <input
              autocomplete="current-password"
              type="password"
              placeholder="********"
              name="password"
              id="password"
              required
            />
          </div>
        </div>
        <!-- Submit Button -->
        <button type="submit" id="submitBtn">
          <span>Sign In to AgriTrack</span>
          <span>arrow_forward</span>
        </button>
      </form>
    </div>
  </main>
</template>
