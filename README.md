# Bootstrap Hamburger Menu

Responsive Hamburger menu with Bootstrap 5. Templates include hamburger menu on the left and on the right (RTL support), icon animations, sidenav, navbar & more.

Hamburger menu is a navigation type that serves the purpose of hiding some menu items & showing them on click. It stacks the items on top of each other in a "hamburger" fashion.

## Basic example

Simple example of hamburger menu in a navbar.

```html
<nav class="navbar navbar-light bg-light">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-mdb-toggle="collapse"
      data-mdb-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent"
      aria-expanded="false" aria-label="Toggle navigation">
      <i class="fas fa-bars"></i>
    </button>
  </div>
</nav>
<div class="collapse" id="navbarToggleExternalContent">
  <div class="bg-light shadow-3 p-4">
    <button class="btn btn-link btn-block border-bottom m-0">Link 1</button>
    <button class="btn btn-link btn-block border-bottom m-0">Link 2</button>
    <button class="btn btn-link btn-block m-0">Link 3</button>
  </div>
</div>
```

#### Much more examples and a detailed description can be found at [📄 Hamburger Menu documentation page](https://mdbootstrap.com/docs/standard/extended/hamburger-menu/)
