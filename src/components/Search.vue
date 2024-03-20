<template>
  <div class="search-container">
    <input
      type="text"
      placeholder="Search a song of your choice"
      class="search-input"
    />
    <button class="search-button">
      <img
        src="https://img.icons8.com/ios-glyphs/30/000000/search.png"
        alt="Search Icon"
      />
      Search
    </button>
  </div>
</template>

<script>
export default {
  name: "Search",
};
</script>

<style scoped>
.search-container {
  display: flex;
  align-items: center;
}

.search-input {
  padding: 10px;
  border: 1px solid #cccccc;
  border-radius: 5px;
  flex: 1;
  margin-right: 10px;
}

.search-button {
  background-color: #000000;
  color: #00ff00;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
  cursor: pointer;
}

.search-button img {
  margin-right: 5px;
}
</style>
