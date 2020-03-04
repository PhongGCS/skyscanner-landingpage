<template>
  <header class="header js-header ">
    <div class="header__container container max-width-lg">
      <div class="header__logo">
        <a href="#0">
          <svg width="130" height="32" viewBox="0 0 130 32"><title>Go to homepage</title><circle fill="var(--color-primary)" cx="16" cy="16" r="16"/><rect fill="var(--color-contrast-higher)" x="41" y="11" width="89" height="10"/></svg>
        </a>
      </div>

      <button class="btn btn--subtle header__trigger js-header__trigger" aria-label="Toggle menu" aria-expanded="false" aria-controls="header-nav">
        <i class="header__trigger-icon" aria-hidden="true" />
        <span>Menu</span>
      </button>

      <nav id="header-nav" class="header__nav js-header__nav" role="navigation" aria-label="Main">
        <div class="header__nav-inner">
          <div class="header__label">Main menu</div>
          <ul class="header__list">
            <li class="header__item"><a href="#0" class="header__link">About</a></li>
            <li class="header__item"><a href="#0" class="header__link">Solutions</a></li>
            <li class="header__item"><a href="#0" class="header__link" aria-current="page">Resources</a></li>
            <li class="header__item"><a href="#0" class="header__link">Pricing</a></li>
            <li class="header__item"><a href="#0" class="header__link">Contact</a></li>
            <li class="header__item header__item--divider" aria-hidden="true"></li>
            <li class="header__item"><a href="#0" class="btn btn--primary">Download</a></li>
          </ul>
        </div>
      </nav>
    </div>
  </header>
</template>
<script>
export default {

}
</script>
