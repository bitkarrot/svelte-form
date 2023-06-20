

<main class="container center-sm">
    <hgroup>
        &nbsp;
      <h1>Contact Us</h1>
      <p>
        Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
      </p>
    </hgroup>

  <form>
    <fieldset>
      <label>
        Your Name
        <input name="name" placeholder="Your Name" />
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
          placeholder="Write your message here....."
          aria-label="message"
        />
      </label>
    </fieldset>

    <input type="submit" value="Send!" />
  </form>
</main>
