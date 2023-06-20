<main class="container center-sm">
    <hgroup>
      <h1>Welcome to SvelteKit</h1>
      <p>
        Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
      </p>
    </hgroup>

  <form>
    <fieldset>
      <label>
        First name
        <input name="first_name" placeholder="First name" />
      </label>
      <label>
        Email
        <input
          type="email"
          name="email"
          placeholder="Email"
          autocomplete="email"
        />
      </label>
      <label>
        Message
        <textarea
          placeholder="Write a professional short bio..."
          aria-label="Professional short bio"
        />
      </label>
    </fieldset>

    <input type="submit" value="Subscribe" />
  </form>
</main>
