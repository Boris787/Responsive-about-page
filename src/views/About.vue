<template>
  <div class="about-card">
    <div class="card-title">
      <img height="50px" src="https://i.pinimg.com/originals/d3/69/d9/d369d9056795f553e244da66e8297cca.png" alt="avatar" class="avatar">
      <div class="title-text-content">
        <p>About me</p>
        <h2>Boris Mrdja</h2>
      </div>
    </div>
    <div class="card-content">

      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
      
      <table width="100%">
        <tr>
          <th>Requirement</th>
          <th>Solution</th>
        </tr>
        <tr>
          <td>Design</td>
          <td>Paint, PixelArt, PhotoShop Master</td>
        </tr>
        <tr>
          <td>Front-end</td>
          <td>Vue.js, Vuetify, HTML. CSS</td>
        </tr>
      </table>

      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>

      <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>

    </div>
  </div>
</template>

<style lang="sass" scoped>
.about-card 
  background: #333
  padding: 3em
  border-radius: 10px
  color: white
  .card-title
    display: flex
    align-items: center
    background: #222
    border-radius: 10px
    .avatar 
      border: 1px solid rgba(255, 255, 255, 0.4)
      border-radius: 50%
      margin: 0 30px
  .title-text-content
    p
      margin-bottom: 0
      color: rgb(210, 210, 210)
    h2
      margin-top: 0
  
.card-content p
  line-height: 1.5
  margin: 30px auto

table
  border-spacing: 0px
  margin: 50px auto
  tr th, tr td
    border: 1px solid white
    border-top: none
    padding: 10px
    text-align: center
    &:first-of-type
      border-left: none
    &:nth-of-type(2)
      border-right: none
</style>
