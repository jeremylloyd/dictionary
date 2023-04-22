<script lang="ts">
  import Nav from "../components/Nav.svelte";
  import SearchBar from "../components/SearchBar.svelte";

  let word: string | null = null;
  let darkMode: boolean = false;
  let font: "sans-serif" | "serif" | "mono" = "sans-serif";
</script>

<div class="page">
  <header>
    <Nav />
    <SearchBar />
  </header>
  <main class="content">
    <h2>No Definitions Found</h2>
    <p>
      Sorry pal, we couldn't find definitions for the word you were looking for.
    </p>
  </main>
</div>
