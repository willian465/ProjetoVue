<template>
  <div>
    <main>
      <div class="text-top">Vídeos novos toda <b>quinta</b> às <b>10h</b></div>

      <a href="https://youtube.com/wdevoficial" target="blank">
        <img
          alt="Inscreva-se"
          id="subscribe"
          src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg"
        />
      </a>

      <div class="text-buttom">
        youtube.com/wdevoficial<b>quinta</b> às <b>10h</b>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>
<style scoped>
main {
  background-color: var(--color-background-home);
  justify-content: center;
  align-items: center;
}

.text-top {
  color: var(--color-text-light);
  font-size: 22px;
  margin-bottom: 20px;
}

.text-buttom {
  color: var(--color-text-light);
  font-size: 18px;
  margin-top: 20px;
}

#subscribe {
  width: 340px;
}

@media (min-whith: 700px) {
  #subscribe {
    width: 370px;
  }
}
</style>
