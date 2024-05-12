# Ex.10 Responsive Web Design using Bootstrap
## Date:12.05.2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
DEVELOPED BY: VESLIN ANISH A
REGISTER NO:212223240175
```
web.html


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url(https://png.pngtree.com/thumb_back/fh260/back_our/20190621/ourmid/pngtree-atmospheric-medical-medical-symbol-gradient-poster-image_202320.jpg);
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #343a40; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="web.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to PharmaCompany</h1>
        <p>Welcome to PharmaCompany, your trusted source for high-quality pharmaceutical products. We are dedicated to improving the health and well-being of our customers by providing safe and effective medications.</p>
        <p>At PharmaCompany, we offer a wide range of prescription and over-the-counter medications to meet your healthcare needs. Whether you're managing a chronic condition or simply looking for relief from minor ailments, we have the products you need.</p>
        <p>Thank you for choosing PharmaCompany for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
       
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
about.html



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('https://png.pngtree.com/thumb_back/fh260/back_our/20190621/ourmid/pngtree-atmospheric-medical-medical-symbol-gradient-poster-image_202320.jpg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
    position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #343a40; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>About PharmaCompany</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>Our vision is to be a leading provider of innovative healthcare solutions that improve the quality of life for people around the world.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission is to develop and deliver safe, effective, and affordable medications that address the healthcare needs of our customers.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Quality: We are committed to maintaining the highest standards of quality in everything we do.</li>
            <li>Integrity: We conduct our business with honesty, transparency, and ethical behavior.</li>
            <li>Innovation: We strive to continuously innovate and improve our products and services to better serve our customers.</li>
            <li>Customer Focus: We are dedicated to understanding and meeting the needs of our customers.</li>
            <li>Teamwork: We work together as a team to achieve our goals and deliver exceptional results.</li>
          </ul>
        </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('https://png.pngtree.com/thumb_back/fh260/back_our/20190621/ourmid/pngtree-atmospheric-medical-medical-symbol-gradient-poster-image_202320.jpg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      height:1px;
      background-co1or: #343a40; 
      color: white;
      text-align: center;
      padding: 5px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="product.html">Products <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>Our Products</h1>
        <div class="card-deck">
          <div class="card">
            <img src="https://zanducare.com/cdn/shop/files/KarelaJuice_1L_46e21227-4e02-4fcb-961b-501543560aff.png?v=1694501280" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Product 1</h5>
              <p class="card-text">Everherb Karela Jamun Juice - Helps Maintains Healthy Sugar Levels -Helps In Weight Management - 1l.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="https://images.apollo247.in/pub/media/catalog/product/C/A/CAL0021_1_1.jpg" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Product 2</h5>
              <p class="card-text">Calcimax Forte Plus Strip Of 30 Tablets.</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBIVERIREREVEREYEhIaERESEhIYERESGBgaGRwYGhgcIS4lHB4rIRgYJzgmKy8zNzU1HDE7QDszPy40NTEBDAwMEA8QHhISHzQjJCM0NjQ2PTgxNDQ0MTQ0NDQ0MTQ0NDQ0NjE0NDQ0NDQ0NDQ0NDQ0NDQ/NDQ0NDQ0MTQ0NP/AABEIANMA7wMBIgACEQEDEQH/xAAcAAEAAQUBAQAAAAAAAAAAAAAABAECAwUHBgj/xABHEAACAQIDAgoECQoHAQEAAAABAgADEQQSIQUxBhMiMkFRYXGB0UJSkbEHI1NygpOhosEzQ1RVkpSy0uHwFBU0YnODwhYX/8QAGQEBAQEBAQEAAAAAAAAAAAAAAAECAwQF/8QAJBEBAQACAAYCAgMAAAAAAAAAAAECEQMEEhMxURQhMmEiQXH/2gAMAwEAAhEDEQA/AOzREQEREBERAREQKTW8IMU1LC16tM2dabFSQDY9djNlNPws/wBBif8AiaIzl4rnQ4R4x+diH+iQv8IEyrtXEnfiKp/7H7O2aWjJ1Pd7f/M7SPBllfbYjHVje9V/zn5x+jd0zIMVUv8AlH3j029XvkNenvqTOu/xX+GVytqSK7+u3pekeyXis/rtuHpHrMwL/N+EvH4D3mE2zis/rtv9Y9UCvU9dun0mmMfiPcJX+sJtlGKqfKP0em3nK/42qN1V+j0285hlp8oXdSBtKuN1Z/2ierrm34NbTrVK7JUfOnFsRotwQyjeB2medPl+E2/BH/Ut/wAT/wAaSZSaduDll1T7e3iInF9EiIgIiICIiAiIgIiICIiAiIgUmi4YuwwNcKjOWULZQSRmIF7AbhN9KQlm5pwR8bTTn1AmpHKuNRvHeJcu38IN9dfY56uodk9b8KOxcKlKnWWgi1amJfjagUZ3vQqudTu5SKdOqcSdzc6zVzsc8eVxy82uijhPgxvretup1Tv+jL14WYL5Zuj81V6Bb1ZzUMeuVzHrk7la+Fh7rpo4W4L5V+n81V6fozInCzBH863Rvp1B71nLw56zJGHR2vlV2tvyhjb2R3KXksPddMHCvBfKn6up5Sh4XYEfnm+qqn3LOdHDVPUqfsP5SNVDKbMGU9TAg/bL3KnwuH7rp3/1+A+Xb6mt/JLl4V4E7sQPFKo/8zleY9czUNbX6/wk7tLyOHuupLt/CNza6nwYe8T0XA7Fq2JvT5asjqWW+VTyW1Nuy3jOXcGKCPiqCOoZWq01ZWAIKs6gix7DPoTAbPpUE4ujTWmmYnKu7MbAn7BL12xictjhlLLUyIiZdyIiAiIgIiICIiAiIgIiICIiBSeY4TcNMLgjxbk1K9r8SlrgHdmY6LfxPZPTz5u4U7TSpTT4scc9XEVKtYk53Z6hsL+qqgKB0SVcZutlwp4e1cYUUgUURi1NaZOYOVZLlzqTldhuA13TxLqCb3ExXlLyWu2MkSKOELmwZB2vURR94zN/lj+vS+up+chXlbyN6TP8tf16X11Pzmajs6sOY6Dur0/5prrzebHx+FRCtfDrUa/Jbi0Y26iTCXcWJs3GHmuD3VkPuMo+wsYxuwues1F85tP832d+iD6ql5zBj9qYN6bqmFyuRyWNOmLHruDeGd301VbY9ddWpk/NIb3XkNVsd/vlplIbbbZu0jSdXU2ZSCrDUqwIIIvpvE6twf8AhOV7LiU6r1KYt4lDe/gfCcUQzaUGta0srGWMfTWExSVEWpTYOjC6su4yROf/AATYlmo4hCbqr02UdRcMD/AJ0CacFYiICIiAiIgIiICIiAiIgIiIFrbjOPJsfCOqF8OjaaZgTa5v7zOwvuPcZyXZX5Gj/wAdP+EQbZ8PwdwP6JRPfTBmwpcGsB+hYf6pPKZcNNjRhd1ETgxs/wDQcN9TT8pITgvs79Aw31FPyk+nJNODda5OC2zv1fhv3en5TMvBPZv6vwv7tS8pskkinButSOCOzf1fhf3al5QeCOzf1fhf3el5TdiGg3WiPBLZn6uwv7vT8pY3BLZn6vw31FPym9MtMG68+3BDZn6vw31SeUwVOCmzxuwdEdyW909E0jVoN1H4M4GjRastGkKYIp5gt7G2a2/vM9DNFsQfHVjY8ynrfQ6v0dc3sIREQEREBERAREQEREBERAREQLW3HunKNnpanTXfZFF+uwtOrtuM5TgRyE+aIEXbe06tJ6a03ygpcjKp1uR0iRU4R4v5QfVp5SZtumjZs7hBxdPl5C1uW+lhrL8JhabVsWGC8nEU8iGwDv8AGZUB6Axt7J6cOnp+4+Xx+5eJZjlZv9vQcE8fUrU3aq2dhUsCFUaZQegds9HTnj+DFNq2GxaFijvUqDMl0KOyAXFubY+6bHYWLfEVqdQlgKWFRaiBjl/xVQ8sEDeUFPwzzlnj/K6ezl8r25v729OgmenPFtTz7HFZnqcYmErOjrWqq2cKxBbKwzc0c682uNZMNgrI7I1U00V3qVHZXqAKzguSRlUM1h6szp26npBBnlBjy2y8UFqMz0Vq0+NDNnYJzXzb7lCpv13m82yrnDVFp1BSdlsjs2QBmIAGboJva++5k0bSqtVVtnZVvuzMBf2wZotiUkLVqT06qOopM+FxFTjkTNmAdHJYlWynp0K7gd++MWaqy7jE01dXaNPdy99r8TWy9+bJa3be02rTy2I2sFr0sJccvCVXPXn9AfspU+yZt06Y4723WxB8dWNjzKet9Dq/R1zezR7FHx1c2PNpa30Or6W6/ObyVgiIgIiICIiAiIgIiICIiAiIgWtuM5VgOYnzR7p1Vt05TgOYnzR7oGs4UORURb2VqYzDTWzNb3ma8YtyXJc3d1dzoCXW9m03WzHd1z3uHUHeAe8SfSpr6q/sid8eLMZrTwcbk8s8rlMtb/TV8CarPTrOxuzVrsbAXJVbmw0npMFhKdPjOLQJnqNUqWvyna12PsllFANwA7gBJSTlllu2vXwsOjGY270sTZ9LiThsg4koyFLtYo1wRe9+k9Mlf4RGamxW7UyTTNzyCVKk26TYka9cqkzpJtvUR6uzqTcbmS/Gqq1tWGcKLC9jpppcS1Nk0FV0yFkcAOtSpUcMBf1mNt/RJwgx9mog4LZ1Kjm4tSC1s7Mzs7W3Au5JsLmwvpeSTLzLTIutMTTSVMBU9ahuIDf4duMybrZ8++3Tbwm7aRq0mmplZ4Y9ij42sb71p6dAsX85u5o9iD46vu5lLrzb33zeSskREBERAREQEREBERAREQEREChnJKFbKtPS91651ozkB5tPu8pZ5Zztk3G4w2O/2fe/pNhS2h/s+9/SeXZqhcLTZVyoGIdbh7sQFv6I5J17RLn2m6nFAZbJSqNS6SWpqM+YdV2UeBm5jt57xcp/b2VPaI9Q+2SF2iPUPtE8xXq1TUWlSZEPFl3eohcWuFChQRvN9b9EsrbSrI2VlQMFwmYDMQGqVjTexuNLC4/GWYSs3jZPYJtIeofaJnTaQ9Q+0Txm0dq1abVBTRXyVMOFWxzMHViw37+Tp+Ml4ba+fE06dPK1FqbEv0l8quFGvQrKT86XoO9l7etG0h6h9og7SHqH2iaF9pUVqiiaihyDpmXRrqAp1vmOYWHTYyYZOmHey9px2mPUPtEsbaY9Q/tf0kAy0yah3cvac20v9n3v6SO+0b6ZN59b+kjNMR3jvHvjUWcXL23OxlHGVj0laY9hfzm6mn2OfjKvcnvabic3rIiICIiAiIgIiICIiAiIgIiIFJyD0afzfKdfnIF1WmSLHLqOrdLj5Yz/ABqlenSY/GZhlS7BS4DIW5pA5wuu7zlxTCEimQ4Z+NGZadTNUzlle7hdRc+GkVsMzvSK80Napr6AZXHfykA+lJGGw9ReLbJcouKuAV1LsGQb+m07R5KuZKGR6hxNQcU7o9YOM6XyhkPJsRfL0b+mSamDwy2pu5UvSVUGclstEmpnB35gTe5msTZddaboyrUD06RfILDjEqAtmu2pYM2o05EzjY9VXRieMyiqiEHmUBSqKgN/SLML9wmvr2w2OGoYc3PHPUdWpV3d2GcqF5BICgZLdAElJSw1IUqoIp0wamTLfK5rAMTaxOoXSaYbLrZXqIhFVcPQRASLVF4opUpnxtbtAm3q0qi0cHamzsj0TURLZwFQg7yBvMl/0iWcRhjlxOdCBmQOCTqxUlco1LXVdLXkujVV0DowZSNGG4zVKlQcbVNBwKlSnZFanx1NVTLxgGq579F729kmbHoulBFdSrA1NDbNYuxBa2mcggntJksEoy0y8ywyCxpiO8d498zNMJ5w7x74q4+W32MBx1c35WWlcdQBqW959k3c0uxsvHV7c7LSv3Xe34zdTi+gREQEREBERAREQEREBERAREQKTkCDkU93M6N24buydfnJculMdh/CXHyxxPxqrMRazhDb0r23+z++2S8PVa/5RGUdC6sRfXcN47PxliU1bnKG7wDJlPDp6gHcLe6dY8lYqVSqMoDo665mtYgKNTbTTVfbJKVaul3o7yALsLnXT3HwmRMLT05A0zW3+kLH7NJd/l9Im+QAk3NidfCXcZV4x8ti6B8yWKmwsb6WN94H92mdKtSzcqlcDQ3NgwOt9dws3shMHTAK5dCNRdtdCOvtPtl6bOpWtxY9rafb2mPpGWiK2YZymXW4UG/ZY9/vkkwIMgsMsMyGWGBFxLE8hecbXOvJHXp3SvSvePfMVY1c7FEQrYBWY2Nt5HtmVL8m+h5N7br6Xirj5bfY5HHVxbXLSuesE1LD7D7Zupp9kfla2vo0+Tbdq+t/73TcTi+gREQEREBERASkRAREQEREBERATkwIK0yNxGndpOszlB1FMjpB/CXHyxxPxqTREm0wf76O6Q6Q3f37ZNpga9m7s06J0eOpCA9fj1zMt9/fp1+MxIBob77a9czIo5t94Ol9f71mmWdJlSYkGtr6WHf075nWQXCUMuAlDAtMsMyGWGBBxGNVagpkEki9wN172HaTlMyg3KkbiVtI2Jem50qICDlbXlAg6he3nDx7JIpOrZGQgqSLEbtDaW+Fx8t1slRxlU9JWn9hfzm1ms2WOXU7k/8AU2c4PoKxKRArEpECsSkQKRLM0ZoF8THmjNAyRMeaM0DJEx5ozQMgnLqg5n0vwnTQ05tXXVfpe8S4+WOJ+NZKK6SbTXdIdJ1BsWAPVcX6/wADJtIg2sQe6dHkqRTXfp/WZkT++mY0EzoJWF6LMyiY1EyqIFwlDIeKw9ZiSlQKuZbLmZTYZb8pdRub2yxsLXOcFwVbjLWeopp5iuUCw1tlPSOcZdCaZaRIVTB1SLcafyikHMwsoL6aanRl77TE+zKjatWcNcmys2UaGw113keztjUEpsLTvcohPWUW8KoBUCwsw0FtNZDq7KLEs1TXNmyheQTfcwvyhrbfM2DwqpZVOblC5Nr793he0XwuPlvNlgcbW33y0766DV9w65tprdmsM9UdIFO/jmtNlOD6CsREBERAREQI9omQy0wLZSVJlCYC8peULS0vAvvKZpjLiUNSBmDTnOJxFPOUFRC6s4ZA65lNxoRe4nv+ME4Nw42S7Yuo6gG7HMp0II06e6N6Lj1TXh7+lhRnz630vusdO7u9nfL02bvIqONNNd2+1rdGpnGKdOunMzp8x2H8JmdNpY1ebiMSP+2tb3zXcYvK2+K7hhMMULctnB3Brmxuxvqe37JNQThScItpDdisR4kn3iTcNwk2mT/q6ijpLLTv4ArL3IxeUy9x25RMiichThRjwP8AVOe0pS1+5Lhwsx/6U31dH+SOuM/Gz9x2AShE5D/9btD9Kb9ij/JIuJ4UbSOqYxwerJSsfHJHXD4uXuOzESJisJnN87LoBp469+o8QN84m/CnanTi6/gFHuWRn2/tFt+LxPhUqD3WjuRqcnl7jtjbLU2u7myhRzdwFurS8yJTp097BQWUsXKgX6+gTg7YzGPz62Jb51WqR9pkmhhHZrlbnrYi/tk7m2vi6819FbIr03NR6bo4uoZkYMLi+lx3zazyHwc4Y08IQel9/Wen3ievmXQiIgIiICIiBgMGZrSmWBgIlhElZZTIIEMrLGUydxYlDSEDWspmF802xoiUOHEDQ1azDrni+FfFucwB4z0hbRh1986e2FU9Ej1tk0n51NW7wINuA4inrukRjad5r8E8I/Oor9sg1eAOCb82R3MRJpqZOIGrHHTsb/Btgzuzj6ZmB/gwwnQ9QfSEaXqjkfHdscb2zrDfBdhvlan3ZZ/+W4f5ap92TR1RyrjI4ydWHwXYb5Wp93yl6/Bhhel6h8R5Ro6o5PnlwM66nwa4Mb85+mZKpcAMEvoE97sZdHVHHqVO89DsTZ6s657hbi5tew7p02hwSwic2ivjNhS2RSXm01HhGkuS/ZlektNUpiyqNARr3ntk9a4kZcMBuFpkFKVlIFSVzzCElwWBlzSt5iCyoEDJeJaBKwLoiICIiAiIgIiICIiAiIgUlIiBSIiAlIiEIiIUiIgBKxECspEQLoiIFYiIH//Z" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Product 3</h5>
              <p class="card-text">Healthkart Calcium Tablets For Men & Women With Vitamin D3 For Complete Bone Health & Joint (60 No).</p>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5"> 
    <p>&copy; 2024 PharmaCompany. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```
```
contact.html



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - PharmaCompany</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url('https://png.pngtree.com/thumb_back/fh260/back_our/20190621/ourmid/pngtree-atmospheric-medical-medical-symbol-gradient-poster-image_202320.jpg');
      background-size: cover;
      background-repeat: no-repeat;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #343a40; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">PharmaCompany</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2>PharmaCompany</h2>
        <address>
          <strong>Address:</strong><br>
          123 ABC street, Chennai<br>
          TamilNadu-600049<br><br>
          <strong>Email:</strong><br>
          pharmacompany@gmail.com<br><br>
          <strong>Phone:</strong><br>
          +91 6380179744
        </address>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany. All rights reserved.</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```


## OUTPUT:
![WhatsApp Image 2024-05-12 at 05 53 52_cd6103a5](https://github.com/veslin23000303/Pharma/assets/151148539/d4ef10ef-679d-4942-b4f2-c36f5c743849)

![WhatsApp Image 2024-05-12 at 06 00 59_61731acb](https://github.com/veslin23000303/Pharma/assets/151148539/c5e03aca-82c0-4756-99de-9d251e91a0a6)

![WhatsApp Image 2024-05-12 at 06 31 29_68afe836](https://github.com/veslin23000303/Pharma/assets/151148539/a40dfb00-72e9-4ec0-8fdc-4cb6cf10cdac)

![WhatsApp Image 2024-05-12 at 06 36 13_86cc7f34](https://github.com/veslin23000303/Pharma/assets/151148539/e905f975-aa21-472d-b981-40a09d19328b)


## RESULT:
The program for responsive web design using Bootstrap is completed successfully.
