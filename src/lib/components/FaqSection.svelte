<script>
  import {FAQItem, Button} from "$components"
  import twitterIcon from "$assets/icons/twitter.webp"
</script>

<section class="faq-section">
  <h2 class="mb-l">Frequently Asked Questions</h2>
  <div class="faq-container">
    <FAQItem />
  </div>
  <div class="additional-info">
    <Button class="mt-s">BUY NOW</Button>
    <p class="mt-m">Any Other Questions?</p>
    <a href="https://x.com">
      <p>
        Hit me up on twitter <img src={twitterIcon} class="twitter-icon" alt="">
      </p>
    </a>
  </div>
</section>

<style>
  .faq-section {
    padding: 80px 0;
    margin-left: 12vw;
    margin-right: 20vw;
    max-width: 1150px;
  }

  .additional-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    color: grey;
  }

  .twitter-icon {
    width: 16px;
    height: 16px;
  }

  .additional-info a {
    text-decoration: underline;
  }
</style>
