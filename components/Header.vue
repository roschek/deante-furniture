<template>
  <header class='container'>
    <div class='logo'>some logo</div>
   <nav class='navigation'>
 <ul class='  navigation-list navigation__head'>
   <li><a class='top__link' href=''>Запасные части</a></li>
   <li><a class='top__link' href=''>О нас</a></li>
   <li><a class='top__link' href=''>Зона профессионалов</a></li>
   <li><a class='top__link' href=''>Контакты</a></li>
   <li><a class='top__link' href=''>Корзина</a></li>
 </ul>
 <ul class=' navigation-list navigation__bottom'>
   <li class='bottom-link'>Продукты</li>
   <li class='bottom-link'>Советы</li>
   <li class='bottom-link'>техническая поддержка</li>
   <li><input type='text' placeholder='Поиск' class='search'></li>
 </ul>
   </nav>
  </header>
</template>

<script>
export default {}
</script>

<style scoped>
.container {
  width: 90%;
  margin: 0 auto;
  text-align: center;
  background: linear-gradient(to right, rgba(2, 71, 141, 1) 0%, rgba(2, 71, 141, 1) 18%, rgba(2, 71, 141, 0.9) 36%, rgba(2, 71, 141, 0.9) 100%);
  padding: 20px;
  display: flex;
  flex-direction: row;
}
.logo{
  font-size: 24px;
  font-weight: bold;
  color: white;
}
.navigation{
  width:90%;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-end;
}
.navigation-list{
  position: relative;
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  margin-right: 0;
  color: white;
  margin-bottom: 10px;
}
.top__link{
  display: block;
  color: #6fb3da;
  margin-right: 40px;
  transition: .3s;
}
.top__link:hover{
  color: #618599;
}
.bottom-link{
  display: block;
  color: white;
  font-size: 22px;
  font-weight: bold;
  margin-right: 50px;
  transition: .3s;
  cursor: pointer;
}
.bottom-link:nth-of-type(3){
  margin-right: 350px;
}
.bottom-link:hover{
  color:lavender;
}
.search{
  position: absolute;
  right: 10px;
  top:0;
  background-color: #6fb3da;
  padding: 10px;
  border: none;
  outline: none;
  color: white;
  width: 300px;
  font-size: 18px;
  transition: .4s;
}
.search::placeholder{
  color: white;
  font-size: 18px;
}
.search:focus{
  width: 400px;
}
</style>
