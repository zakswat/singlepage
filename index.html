<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <title>jquery test</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:400,500|Open+Sans" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

    <style type="text/css">
        .bs-example{
            margin: 100px;
            height: 100%;
        }
    </style>
</head>
<body>
<div class="bs-example container">
    <div class="row">
        <div class="col-sm-4">
            <form id="mainform">
                <div class="form-group">
                    <label for="fname">First name</label>
                    <input type="text" class="form-control" id="fname" placeholder="Enter your first name" name="firstname">
                </div>
                <div class="form-group">
                    <label for="lname">Last name</label>
                    <input type="text" class="form-control" id="lname" placeholder="Enter your last name" name="lastname">
                </div>
                <div class="form-group">
                    <label for="email">Email address</label>
                    <input type="email" class="form-control" id="email" placeholder="Enter your email" name="email">
                    <small id="emailHelp" class="form-text text-muted">We'll never share your email with anyone else.</small>
                </div>

                <button type="submit" class="btn btn-primary" id="submit">Submit</button>
            </form>
        </div>

        <div class="col-sm-8">
            <table class="table">
                <thead>
                <tr>
                    <th scope="col">First</th>
                    <th scope="col">Last</th>
                    <th scope="col">email</th>
                    <th scope="col">Edit</th>
                    <th scope="col">Delete</th>
                </tr>
                </thead>
                <tbody>

                </tbody>
            </table>
        </div>
    </div>
    <hr>
    <div class="frows">
        <button type="button" class="btn btn-info" id="findrows">how many rows in this table</button>
    </div>
</div>

<script
        src="https://code.jquery.com/jquery-3.4.1.js"
        integrity="sha256-WpOohJOqMqqyKL9FccASB9O0KwACQJpFTUBLTYOVvVU="
        crossorigin="anonymous"></script>
<script src = "https://cdnjs.cloudflare.com/ajax/libs/jquery-validate/1.19.1/jquery.validate.js"></script>

<script>

    //form submitting
    var $num = 0;
    var currentRow = null;
    $('#mainform').on("submit",function(e){
        e.preventDefault();
        if ($(this).valid()) {
            var $fname = $('#fname').val();
            var $lname = $('#lname').val();
            var $email = $('#email').val();

            $num++;
            var $tr = $('<tr>');


            $tr.html('<td class="tfname">' + $fname + '</td>' +
                '<td class="tlname">' + $lname + '</td>' +
                '<td class="temail">' + $email + '<td>' +
                '<button type="submit" class="btn btn-primary" id="edit">Edit</button></td>' +
                '<td><button type="submit" class="btn btn-danger" id="delete">Delete</button></td>');
            this.reset();

            if (currentRow) {
                var $nr = $('<tr>').html('<td class="tfname">' + $fname + '</td>' +
                    '<td class="tlname">' + $lname + '</td>' +
                    '<td class="temail">' + $email + '<td>' +
                    '<button type="submit" class="btn btn-primary" id="edit">Edit</button></td>' +
                    '<td><button type="submit" class="btn btn-danger" id="delete">Delete</button></td>');

                $("table tbody").find($(currentRow)).replaceWith($nr);
                currentRow = null;
                this.reset();
            } else {
                $('tbody').append($tr);
            }
        }

    });

    //delete a row
    $('table').on('click','#delete',function () {
        $(this).closest('tr').remove();
    });

    //edit row
    $('table').on('click','#edit',function () {
        currentRow= $(this).parents('tr');

        var col1=currentRow.find("td:eq(0)").text(); // get current row 1st TD value
        var col2=currentRow.find("td:eq(1)").text(); // get current row 2nd TD
        var col3=currentRow.find("td:eq(2)").text(); // get current row 3rd TD


        $('#fname').val(col1);
        $('#lname').val(col2);
        $('#email').val(col3);
    });

    //form validation
    $('#mainform').validate({
        rules: {
            firstname: "required",
            lastname: "required",
            email: {
                required: true,
                email: true
            },
            messages: {
                firstname: "please enter your first name",
                lastname: "please enter your last name",
                email: "please enter a valid email address"
            }
        }

    });

    //form validation ends

    //count rows in the table

    $('#findrows').on('click',function () {
        alert($('.table tbody tr').length);

    });

    $('body').on('click',function (event) {
        var $div = $('<div>').width(100).height(100).css('background','red').css('position','absolute').css("top", event.pageY + "px")
            .css("left", event.pageX + "px");
        $div.appendTo('body');
    });

</script>

</body>
</html>