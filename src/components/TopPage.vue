<template>
  <div id="top">
        <span
          class="type-js"
          v-resize-text="{minFontSize: '30px', maxFontSize: '200px', delay: 1}"
        >
          <b>
            <vue-typer
              erase-style="backspace"
              :text="['Hi! I\'m Yusuke!', 'I\'m a Software Engineer! :)']"
              :repeat="0"
              :erase-delay="100"
              :type-delay="100"
              caret-animation='blink'
            ></vue-typer>
          </b>
        </span>
  </div>
</template>

<style scoped>
#top {
  height: 150px;
  margin: auto;
  text-align: center;
  display: -webkit-flex;
  display: flex;
  -webkit-align-items: center; /* 縦方向中央揃え（Safari用） */
  align-items: center; /* 縦方向中央揃え */
  -webkit-justify-content: center; /* 横方向中央揃え（Safari用） */
  justify-content: center; /* 横方向中央揃え */
  padding: 20px;
}

.type-js {
  text-align: center;
  display: inline-block;
}

.custom.char.typed {
  color: #009688 !important;
}

</style>
Thank you for your email :)
I sent you a message with my email, ykoba16@gmail.
But I forgot to put a subject on the mail, soryy.
Yu

<script>
import { VueTyper } from "vue-typer";
import ResizeText from "vue-resize-text";

export default {
  components: {
    VueTyper
  },
  directives: {
    ResizeText
  }
};
</script>