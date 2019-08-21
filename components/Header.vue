<template>
  <div>
    <div uk-sticky="sel-target: .uk-navbar-container; cls-active: uk-navbar-sticky; bottom: #transparent-sticky-navbar">
      <nav class="uk-navbar-container"  uk-navbar style="position: relative; z-index: 980;">
        <div class="uk-navbar-left">
          <!-- <a class="uk-navbar-toggle" href="#">
            <span uk-navbar-toggle-icon></span>
            <span class="uk-margin-small-left">Menu</span>
          </a> -->
          <a class="uk-navbar-item uk-logo" href="#">Laxis Market</a>
          <div class="uk-navbar-item">
            <form action="javascript:void(0)">
              <input class="uk-input uk-form-width-medium" type="text" placeholder="Rechercher" />
              <button class="uk-button uk-button-default uk-text-capitalize">Trouver</button>
            </form>
          </div>
        </div>
        <div class="uk-navbar-right">
          <div class="uk-navbar-nav">
            <li>
              <a href class="uk-text-capitalize">
                <div class="uk-text-center">
                  <span uk-icon="location"></span>
                  <div class="uk-navbar-subtitle">Kinshasa</div>
                </div>
              </a>
            </li>
            <li>
              <a href class="uk-text-capitalize">
                <div class="uk-text-center">
                  <span uk-icon="heart"></span>
                  <div class="uk-navbar-subtitle">Mes favoris</div>
                </div>
              </a>
            </li>
            <li>
              <a href class="uk-text-capitalize">
                <div class="uk-text-center">
                  <span uk-icon="cart"></span>
                  <div class="uk-navbar-subtitle">Mon panier</div>
                </div>
              </a>
            </li>
            <li>
              <a href class="uk-text-capitalize">
                <div class="uk-text-center">
                  <span>
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"><path class="n-chat-icon n-chat-icon_color_gray" fill-rule="evenodd" d="M7.888 16c-3.474-.003-6.537-2.31-7.543-5.682-1.006-3.373.28-7.015 3.17-8.971a7.8 7.8 0 0 1 9.385.47c2.685 2.235 3.611 5.989 2.282 9.244a3.123 3.123 0 0 0-.172 1.948v.017l.675 2.339a.448.448 0 0 1-.114.426.434.434 0 0 1-.42.116l-2.255-.672a2.99 2.99 0 0 0-1.989.158A7.769 7.769 0 0 1 7.888 16zm-.012-4.25c2.042 0 3.698-1.679 3.698-3.75 0-2.071-1.656-3.75-3.698-3.75S4.18 5.929 4.18 8c0 2.071 1.655 3.75 3.697 3.75z"></path></svg>
                  </span>
                  <div class="uk-navbar-subtitle">Chats</div>
                </div>
              </a>
            </li>
            <li>
              <a href>
                <button class="uk-button uk-button-primary uk-rounded">Se connecter</button>
              </a>
            </li>
          </div>
        </div>
      </nav>
    </div>
    <nav class="uk-navbar-container" uk-navbar>
      <div class="uk-navbar-left">
        <a class="uk-navbar-toggle uk-text-capitalize" href="#">
          <span uk-navbar-toggle-icon></span>
          <span class="uk-margin-small-left">Toutes les catégories</span>
        </a>
        <div class="uk-navbar-nav">
          <li>
            <a href class="uk-text-capitalize">Réductions &amp; promotions</a>
          </li>
          <li>
            <a href class="uk-text-capitalize">Eléctronique</a>
          </li>
          <li>
            <a href class="uk-text-capitalize">Construction</a>
          </li>
          <li>
            <a href class="uk-text-capitalize">Vêtements</a>
          </li>
          <li>
            <a href class="uk-text-capitalize">Appareils ménagers</a>
          </li>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>
