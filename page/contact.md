---
layout: default
title: Contact
permalink: /contact
nav_order: 6
---
 <form accept-charset="UTF-8" action="https://getform.io/f/7a547488-c2b9-4756-a2e1-5bba8faaa1af" method="POST" enctype="multipart/form-data" target="_blank">
      <div class="form-group">
        <label for="exampleInputEmail1" required="required">Email address</label>
        <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
      </div>
      <div class="form-group">
        <label for="exampleInputName">Name</label>
        <input type="text" name="name" class="form-control" id="exampleInputName" placeholder="Enter your name" required="required">
      </div>
      <div class="form-group">
        <label for="exampleFormControlSelect1">Favourite Platform</label>
        <select class="form-control" id="exampleFormControlSelect1" name="platform" required="required">
          <option>Github</option>
          <option>Gitlab</option>
          <option>Bitbucket</option>
        </select>
      </div>
 
           <div class="control-group form-group">
            <div class="controls">
              <label>Message:</label>
              <textarea rows="10" cols="100" class="form-control" name="message" required data-validation-required-message="Please enter your message" maxlength="999" style="resize:none"></textarea>
            </div>
          </div>
          <div id="success"></div>
          <!-- For success/fail messages -->
 
      <hr>
      <div class="form-group mt-3">
        <label class="mr-2">Upload your CV:</label>
        <input type="file" name="file">
      </div>
      <hr>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
