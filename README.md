# lesson-modals

Modals

http://v4-alpha.getbootstrap.com/components/modal/

For this lesson, we will learn how to use a bootstrap modal in your project.

Step 1:

inluded your bootstrap links in your head

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css">


Step 2:

Include bootstrap and Jquery in a script tag at the end of your body

<script src="http://code.jquery.com/jquery-2.1.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>

Step 3:

Include the html bootstrap code in your


<!-- Trigger the modal with a button -->
<button type="button" class="btn btn-info btn-lg" data-toggle="modal" data-target="#myModal">Open Modal</button>

<!-- Modal -->
<div id="myModal" class="modal fade" role="dialog">
  <div class="modal-dialog">

    <!-- Modal content-->
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal">&times;</button>
        <h4 class="modal-title">Modal Header</h4>
      </div>
      <div class="modal-body">
        <p>Some text in the modal.</p>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
      </div>
    </div>

  </div>
</div>



Note: your trigger, in this case is a button, will activate your modal on click.

To activate a modal on click of an img for example, data-toggle and data-target from the trigger needs to be included
in your img tag

<img src='something.jpg'   data-toggle="modal" data-target="#myModal"     />

<div data-toggle="modal" data-target="#myModal" > Content </div>
