<template>
  <div class="coffee">
    <button class="menu-btn" @click="$router.push('/Navigation')">
      <img src="../assets/graphics/navicon.svg" />
    </button>
    <h1>Vårt Kaffe</h1>
    <!-- a comment for pull request! -->
    <h4>
      Pumpkin spice mug, barista cup, sit
      macchiato, kopi-luwak, doppio, grounds
      dripper, crema, strong whipped, variety
      extra iced id lungo half and half mazagran.
      Pumpkin spice.
    </h4>

    <p>
      Que dark fair trade, spoon decaffeinated, barista
      wings whipped, as rich aftertaste, con panna milk
      black, arabica white rich beans single shot extra
      affogato. So affogato macchiato sit extraction
      instant grinder seasonal organic, turkish single shot,
      single origin, and robusta strong to go so dripper.
      Viennese froth, grounds caramelization skinny
      aromatic cup kopi-luwak, fair trade flavour,
      frappuccino medium, café au lait flavour cultivar ut
      bar instant kopi-luwak.
    </p>

    <p>
      Roast id macchiato, single shot siphon mazagran
      milk fair trade est aroma a half and half and, so,
      galão iced to go, whipped as cream cup pumpkin
      spice iced. At extra, rich grinder, brewed to go,
      steamed half and half at, that, percolator macchiato
      trifecta and body as arabica dripper. In galão black
      java milk sit trifecta, robusta, acerbic café au lait instant shop latte.
      <br />
      <br />Stop right there criminal scum! You violated the law. Pay the court a fine or serve your sentence. Your stolen goods are now forfeit.
    </p>
    <div class="person">
      <img class="VD" src="../assets/graphics/eva-cortado.jpg" alt="Eva Cortado" />
      <h2>Eva Cortado</h2>
      <h5>VD & Grundare</h5>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
@import url("https://fonts.googleapis.com/css?family=Open+Sans&display=swap");

.coffee {
  padding: 6rem 1.3rem;
  box-sizing: border-box;
  background-image: url("../assets/graphics/graphics-header.svg"),
    url("../assets/graphics/graphics-footer.svg");

  background-position: top center, bottom center;
  background-repeat: no-repeat, no-repeat;
  background-size: 100%, 100%;
  background-color: #f3e4e1;
  color: black;
}
h1 {
  padding-top: 20px;
  font-family: "PT Sans", sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 42px;
  // line-height: 120%;
}
h4 {
  font-weight: bold;
  font-family: "Open Sans", sans-serif;
  text-align: center;
}
.VD {
  border-radius: 50%;
}
p {
  font-family: "Work Sans", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 160%;
}
.person {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.menu-btn {
  margin-top: -20px;
  border: none;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  cursor: pointer;
  width: 4.8rem;
  height: 4.8rem;
  border-radius: 50%;
  background-color: white;
  box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
}
.menu-btn img {
  width: 2.6rem;
  height: 2rem;
}
</style>



