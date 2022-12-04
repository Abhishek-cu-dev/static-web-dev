<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta charset="UTF-8">
    <link rel="stylesheet" href="newform.css">
</head>

<body>
    <div class="bg">
        <h1 class="para">Unknown Form</h1>

        <div class="background ">

            <div class="mar">
                <form class="needs-validation" novalidate>
                    <div class="form-row mo">
                        <div class="col-md-6 mb-3">
                            <label for="validationCustom01">First name</label>
                            <input type="text" class="form-control mo" onKeyPress="if(this.value.length==15) return false;" id="validationCustom01" placeholder="Mark" required>
                            <div class="invalid-feedback">
                                Please Enter your name
                            </div>
                            <div class="valid-feedback">
                                Nice One
                            </div>
                        </div>
                        <div class="col-md-6 mb-3">
                            <label for="validationCustom02">Last name</label>
                            <input type="text" class="form-control mo" id="validationCustom02" onKeyPress="if(this.value.length==15) return false;" placeholder="Otto" required>
                            <div class="invalid-feedback">
                                Please Enter your name
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                    </div>
                    <div class="form-row">
                        <div class="form-group col-md-6">
                            <label for="validationCustom03" class="mo">Email</label>
                            <input type="email" class="form-control mo" id="validationCustom03" placeholder="abc@gmail.com" required>
                            <div class="invalid-feedback">
                                Please Enter your Email
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                        <div class="form-group col-md-6">
                            <label for="validationCustom04" class="mo">Password</label>
                            <input type="password" class="form-control mo" onKeyPress="if(this.value.length==8) return false;" aria-describedby="passwordHelpBlock" id="validationCustom04" placeholder="Password" required>

                            <small id="passwordHelpBlock" class="form-text text-muted mo">Your password never exceed 8 characters.</small>
                            <div class="invalid-feedback">
                                Please Enter your Password
                            </div>
                            <div class="valid-feedback">
                                Verified
                            </div>
                        </div>
                    </div>

                    <div>
                        <p class="mo">Choose your Gender</p>
                        <div class="custom-control custom-radio mo">
                            <input type="radio" class="custom-control-input" id="customControlValidation2" name="radio-stacked" required>
                            <label class="custom-control-label" for="customControlValidation2">Male</label>
                        </div>
                        <div class="custom-control custom-radio mb-3 mo">
                            <input type="radio" class="custom-control-input" id="customControlValidation3" name="radio-stacked" required>
                            <label class="custom-control-label" for="customControlValidation3">Female</label>
                            <div class="invalid-feedback">Please select your gender</div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                    </div>
                    <div class="form-group">
                        <label for="inputAddress" class="mo">Address</label>
                        <input type="text" class="form-control mo" id="inputAddress" placeholder="1234 Main St" required>
                        <div class="invalid-feedback">
                            Please enter your Address
                        </div>
                        <div class="valid-feedback">
                            Next
                        </div>
                    </div>
                    <div class="form-group">
                        <label for="inputAddress2" class="mo">Address 2</label>
                        <input type="text" class="form-control mo" id="inputAddress2" placeholder="Apartment, studio, or floor" required>
                        <div class="invalid-feedback">
                            Please enter your Address
                        </div>
                        <div class="valid-feedback">
                            Next
                        </div>
                    </div>
                    <div class="form-row">
                        <div class="form-group col-md-4">
                            <label for="inputCity" class="mo">City</label>
                            <input type="text" class="form-control" id="inputCity" required>
                            <div class="invalid-feedback">
                                Please enter your City
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                        <div class=" col-md-4 mb-4">
                            <label class="mo">State</label>
                            <select class="custom-select mo" required>
                                <option value="">Choose...</option>
                                <option value="1">Tamil Nadu</option>
                                <option value="2">Andhra Pradesh</option>
                                <option value="3">Karnataka</option>
                                <option value="3">kerela</option>
                            </select>
                            <div class="invalid-feedback">
                                Please Select your State
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                        <div class="form-group col-md-3">
                            <label for="inputZip" class="mo">Zip</label>
                            <input type="number" class="form-control" onKeyPress="if(this.value.length==6) return false;" id="inputZip" required>
                            <div class="invalid-feedback">
                                Please enter your Pincode
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>

                    </div>



                    <div class="form-row">
                        <div class="form-group col-md-7">
                            <label for="phone" class="mo">Enter your phone number:</label>
                            <input type="number" id="phone" class="form-control" onKeyPress="if(this.value.length==10) return false;" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required>
                            <div class="invalid-feedback">
                                Please enter your phone number
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                        <div class="form-group col-md-4">
                            <label for="quantity" class="mo">Choose your age:</label>
                            <input type="number" id="quantity" onKeyPress="if(this.value.length==2) return false;" placeholder="Between 1 to 60" class="form-control mo" min="1" max="60" required>
                            <div class="invalid-feedback">
                                Please enter your age
                            </div>
                            <div class="valid-feedback">
                                Next
                            </div>
                        </div>
                    </div>
                    <div class="form-group">
                        <label for="iu" class="mo">Date of Birthday</label><br>
                        <input type="date" class="form-control mo" id="iu" name="iu" required>
                        <div class="invalid-feedback">
                            Please Select your DOB
                        </div>
                        <div class="valid-feedback">
                            Next
                        </div>
                    </div>
                    <div class="custom-file mb-3 mo">
                        <input type="file" class="custom-file-input" id="validatedCustomFile" required>
                        <label class="custom-file-label" for="validatedCustomFile">Signature</label>
                        <div class="invalid-feedback">
                            Please Select the file
                        </div>
                        <div class="valid-feedback">
                            Finish!
                        </div>
                    </div>
                    <div class="cen">
                        <button class="btn btn-primary" type="submit">Submit form</button>
                    </div>
                </form>







            </div>

        </div>

        <div class="bu">
            <hr class="dot">

            <p class="para-1 pa">Note: </p>
            <p class=" para-1 pa pu">This form is from anonymous source so do not enter your personal details &#128517;</p>
        </div>
    </div>

    <script>
        // Example starter JavaScript for disabling form submissions if there are invalid fields
        (function() {
            'use strict';
            window.addEventListener('load', function() {
                // Fetch all the forms we want to apply custom Bootstrap validation styles to
                var forms = document.getElementsByClassName('needs-validation');
                // Loop over them and prevent submission
                var validation = Array.prototype.filter.call(forms, function(form) {
                    form.addEventListener('submit', function(event) {
                        if (form.checkValidity() === false) {
                            event.preventDefault();
                            event.stopPropagation();
                        }
                        form.classList.add('was-validated');
                    }, false);
                });
            }, false);
        })();
    </script>

</body>

</html>
