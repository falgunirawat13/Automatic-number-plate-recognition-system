# Automatic-number-plate-recognition-system

For Front end :
Html code:<html>
    <head>
        <link rel="stylesheet" href="css.css">
        <script src="js.js"></script>
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    </head>
    <body>
        
    
<div class="container py-5">

    <!-- For demo purpose -->
    <header class="text-white text-center">
        <h1 class="display-4">Automatic Number Plate Detection System</h1>
        <!--<p class="lead mb-0">Upload image of your vehicle below</p>-->
        <p class="mb-5 font-weight-light">Detected number will be shown here</p>
        <img src="https://bootstrapious.com/i/snippets/sn-img-upload/image.svg" alt="" width="150" class="mb-4">
    </header>


    <div class="row py-4">
        <div class="col-lg-6 mx-auto">

            <!-- Upload image input-->
            <div class="input-group mb-3 px-2 py-2 rounded-pill bg-white shadow-sm">
                <input id="upload" type="file" onchange="readURL(this);" class="form-control border-0">
                <label id="upload-label" for="upload" class="font-weight-light text-muted">Choose file</label>
                <div class="input-group-append">
                    <label for="upload" class="btn btn-light m-0 rounded-pill px-4"> <i class="fa fa-cloud-upload mr-2 text-muted"></i><small class="text-uppercase font-weight-bold text-muted">Choose file</small></label>
                </div>
            </div>

            <!-- Uploaded image area-->
            <p class="font-italic text-white text-center">The image uploaded will be rendered inside the box below.</p>
            <div class="image-area mt-4"><img id="imageResult" src="#" alt="" class="img-fluid rounded shadow-sm mx-auto d-block"></div>

        </div>
    </div>
</div>
</body>
</html>
