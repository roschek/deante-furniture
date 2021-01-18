<template>
  <footer class='container'>
    <div class='footer-list'>
      <ul class='left-side'>
        <li class='left-side_item'>
          <h2>наши витрины</h2>
          <a href=''>Продукты</a>
          <a href=''>Выделенные продукты</a>
          <a href=''>Цветная арматура</a>

        </li>
        <li class='left-side_item'>
          <h2>Продукты</h2>
          <a href=''>Смесители</a>
          <a href=''>Кухонные мойки</a>
          <a href=''>Кабины и поддоны</a>
          <a href=''>Души</a>
          <a href=''>Керамика для ваннойы</a>

        </li>
        <li class='left-side_item'>
          <h2>Зона профессионалов</h2>
          <a href=''>Технические чяертежи</a>
          <a href=''>Модели 3D</a>
          <a href=''>Инструкция и гарантийные карты</a>
          <a href=''>Фотографии высокого качества</a>
          <a href=''>Презентации PowerPoint</a>
          <a href=''>Атестаты</a>
          <a href=''>Bдохновение</a>
          <a href=''>Метаморфозы интерьера</a>
          <a href=''>Часто задаваемые вопросы</a>
        </li>
      </ul>
      <div class='right-side'></div>
    </div>
    <div class='copyright'></div>
  </footer>
</template>

<script>
export default {}
</script>

<style scoped>
.container{
  width: 100%;
  padding: 50px 100px;
  background-color: lightgray;
  display: flex;
  flex-direction: column;
  border-top: 1px solid gray;
}
.footer-list{
  display: flex;
  flex-direction: row;
  border-bottom: 1px solid gray;
  padding-bottom: 20px;
}
.left-side{
  display: flex;
  flex-direction: row;
  color: gray;
}
.left-side_item{
  display: flex;
  flex-direction: column;
  margin-right: 40px;
}
.left-side_item a{
  color: gray;
  transition: .3s;
}
.left-side_item a:hover{
  text-decoration: underline;
}
</style>
