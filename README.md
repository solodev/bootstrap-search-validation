# bootstrap-search-validation
Validation on search bars often goes overlooked. However, to prevent users from being able to search for empty queries, add some simple validation using Bootstrap validator.

## Tutorial
For detailed instruction's, view Solodev's [How to Add Validation to Your Search Bar with Bootstrap Validator](http://www.solodev.com/blog/web-design/how-to-add-validation-to-your-search-bar-with-bootstrap-validator.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/jeL2kn4u/).

## HTML
The tutorial contains the following basic HTML markup.

```
<section class="hero">
  <div class="container">
    <div class="row">
      <div class="col-12">
        <div class="search">
          <form action="" data-toggle="validator" data-focus="false" role="form">
            <div class="form-group has-error has-danger">
              <span><i class="fa fa-times-circle"></i></span>
              <input class="input" type="text" name="q" placeholder="How may we help you?" required data-error="Please enter a search term">
              <button type="submit" class="disabled"><i class="fa fa-search"></i></button>
              <div class="help-block with-errors">
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>
```

## CSS
All required CSS is contained with style.css

## JS
All required JS is contained with search.js

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```