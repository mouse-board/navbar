# navbar
Bootstrap navbar snippet

~~~html
<!-- Navbar Start -->
<nav class="navbar navbar-expand-md navbar-dark bg-dark">
<div class="container-fluid">
    
    <div class="mx-auto order-0">
    <a class="navbar-brand mx-3" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarID" aria-controls="navbarID" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    </div>
    
    <div class="navbar-collapse collapse w-100 order-1 order-md-0 dual-collapse2"  id="navbarID">
    <ul class="navbar-nav me-auto">
        <li class="nav-item active">
        <a class="nav-link" href="#">Left</a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="#">Link 1</a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="#">Link 2</a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="#">Link 3</a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="#">Link 4</a>
        </li>
    </ul>
    </div>

    <div class="navbar-collapse collapse w-100 order-3 dual-collapse2"  id="navbarID">
    <ul class="navbar-nav ms-auto">
        <li class="nav-item">
        <a class="nav-link" href="#">Right</a>
        </li>
        <li class="nav-item">
        <a class="nav-link" href="#">Link R</a>
        </li>
    </ul>
    </div>

</div>
</nav>
<!-- Navbar End -->
~~~
