<template>
  <div class="about-us">
    <h1 class="title-underlined-left">О нас</h1>
    <p class="about-us_text">
      Есть три основных способа зарабатывать на подкастах — это реклама в подкастах уже собравших
      свою аудиторию, подкасты, сделанные вместе с брендами и краудфандинг (когда аудитория так
      полюбила вас, что готова поддерживать деньгами). Конечно бывают еще и платные сервисы, которые
      распространяют подкасты за деньги. Но в России, где рынок пока только развивается, заработать
      таким образом непросто. Хотя есть и удачные примеры. Например, Arzamas распространяет свои
      подкасты через специальное приложение Радио. Арзамас.
    </p>
  </div>
</template>

<script>
export default {
  name: 'AboutUs',
};
</script>

<style scoped lang="scss">
.about-us {
  margin-bottom: 10%;

  &_text {
    width: 50%;
    margin: 0 auto;
    font-family: $font-family-Lora;
    font-size: $font-size-text;
    @media screen and (max-width: $mq-mob) {
      width: 90%;
    }
  }
}
</style>
