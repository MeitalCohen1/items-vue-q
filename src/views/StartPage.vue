<template>
  <div class="allPage">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Abril+Fatface&family=Cookie&family=Dancing+Script:wght@500&display=swap"
        rel="stylesheet">

    <div class="headLine column" style="align-items: center">
      <p style="font-size: 46px">Get Sweety</p>

      <p dir="rtl" style="font-family:Arial,sans-serif; font-size: small; color: gray; margin-bottom: 15px; text-align: center">
        מציעים לך מתכונים מתוקים בהתאם למרכיבים שיש ברשותך במטבח :)
      </p>
    </div>

    <div class="img">
      <img style=" height: 350px; width: 400px; margin-bottom: 70px; opacity: 0.8; margin-block: auto"
           src="../assets/startPic2.jpg">
    </div>

    <div class="btns column" style="width: 200px">
      <q-btn style="margin-bottom: 10px" rounded color="deep-orange-4" label="הירשם" @click="$router.push('/auth')"/>
      <q-btn style="margin-bottom: 10px" rounded color="deep-orange-4" label="התחבר" @click="$router.push('/auth')"/>
    </div>

  </div>
</template>

<script>

export default {
  name: "StartPage",
}
</script>

<style scoped>

.allPage {
  display: flex;
  flex-direction: column;
  justify-items: center;
  align-items: center;
  background-color: #E9E4E5FF;
  padding: 110px;
}

.headLine {
  color: #fd7862;
  margin-top: -30px;
  font-family: 'Cookie', cursive;
}

.btns {
  margin: 30px;
}

</style>
