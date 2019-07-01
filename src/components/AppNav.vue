<template>
  <div>
    <nav>
      <ul>
        <li>Where in the world?</li>
        <li>
          <img src="../assets/moon-regular.svg" width="20" />
          Dark Mode
        </li>
      </ul>
    </nav>
  </div>
</template>

<style lang="scss" scoped>
nav {
  ul {
    list-style: none;
    li:first-child {
      float: left;
      font-size: 24px;
      font-weight: 700;
    }
    li:last-child {
      float: right;
    }
  }
}
</style>
