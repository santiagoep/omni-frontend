<template>
  <li class="message-left" hidden style="display: list-item;">
    <div class="messageinner" hidden style="display: block;">
      <span
        class="message-text"
      >We are young team of entrepreneurs, developers, designers and visionaries. We are based in Berlin and started working on Freedactics in early 2015.</span>
      <span class="message-time">19:58</span>
    </div>
  </li>
</template>

<script>
export default {};
</script>

<style scoped>
.message-left .message-time {
  display: block;
  font-size: 12px;
  text-align: left;
  padding-left: 30px;
  padding-top: 4px;
  color: var(--text);
  font-family: Courier;
}

.message-left {
  text-align: left;
  margin-bottom: 16px;
}

.message-left .message-text {
  max-width: 80%;
  display: inline-block;
  background: var(--secondary-color);
  padding: 15px;
  font-size: 14px;
  color: black;
  border-radius: 30px;
  font-weight: 100;
  line-height: 1.5em;
}

.messageinner {
  -webkit-animation: fadein 2s; /* Safari, Chrome and Opera > 12.1 */
  -moz-animation: fadein 2s; /* Firefox < 16 */
  -ms-animation: fadein 2s; /* Internet Explorer */
  -o-animation: fadein 2s; /* Opera < 12.1 */
  animation: fadein 2s;
}

@keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Firefox < 16 */
@-moz-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Safari, Chrome and Opera > 12.1 */
@-webkit-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Internet Explorer */
@-ms-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

/* Opera < 12.1 */
@-o-keyframes fadein {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
</style>