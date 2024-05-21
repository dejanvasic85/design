<h1>Welcome to our design system!</h1>

<p>
	Create your package using <strong>@sveltejs/package and preview/showcase</strong> your work with
	<a href="https://kit.svelte.dev">SvelteKit</a>. Lorem ipsum dolor sit amet, consectetur adipiscing
	elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
	quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure
	dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur
	sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est
	laborum.
</p>

<h2>We use Svelte</h2>

<blockquote>
	Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
	<strong>Lorem ipsum dolor sit amet, consectetur adipiscing elit</strong>, sed do eiusmod tempor
	incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
	ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
	voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
	proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</blockquote>

<h3>Lorem ipsum</h3>
<h4>Lorem ipsum</h4>
<h5>Lorem ipsum</h5>

<div class="grid">
	<p>
		Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
		labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
		laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
		voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
		non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</p>

	<ul>
		<li>The hunger games</li>
		<li>Harry potter</li>
		<li>Lord of the rings</li>
	</ul>
</div>

<hr />

<form>
	<div class="flex">
		<div>
			<label for="name">Text:</label>
			<input type="text" id="name" name="name" placeholder="Placeholder" />
		</div>
		<div>
			<label for="email">Email:</label>
			<input type="email" id="email" name="email" />
		</div>
		<div>
			<label for="sex">Select:</label>
			<select id="sex">
				<option value="Male">Male</option>
				<option value="Female">Female</option>
			</select>
		</div>
	</div>

	<div>
		<label for="detail">Textarea:</label>
		<textarea id="detail" name="detail">Default value</textarea>
	</div>

	<div class="flex flex-start gap">
		<button type="submit">Submit</button>
		<button class="cancel">Cancel</button>
		<button disabled>Disabled</button>
		<button>button with really long text</button>
		<button>Button &xrarr;</button>
		<button class="small">Button small</button>
	</div>
</form>
