<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
  <title>Survey Form</title>
</head>
  
  <body>
    
    <div class="container">
    <header>
      <h1 id="title">freeCodeCamp Survey Form</h1>

      <p id="description">
        Thank you for taking the time to help us improve the platform</p>
      
     </header>
    
    <form id="survey-form">
      
      <div class="group-form">
        
        <label id="name-label" for="name" >Name <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmQPY6uzN1zl0-bNw7kcR46wqcbB0VnmB3Cw&usqp=CAU" alt=""></label>
        <input 
          type="text" 
          id="name" 
          name="name" 
          class="form-control"
          placeholder="Enter your name" required="">
        
        </div>
        
          <div class="group-form">
            
         <label id="email-label" for="email" >Email <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmQPY6uzN1zl0-bNw7kcR46wqcbB0VnmB3Cw&usqp=CAU" alt=""></label>
        <input 
          type="email" 
          id="email" 
          name="email" 
          class="form-control"
          placeholder="Enter your email" required>
            </div>
        
            <div class="group-form">

              <label id="number-label" for="number" required>Age 
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmQPY6uzN1zl0-bNw7kcR46wqcbB0VnmB3Cw&usqp=CAU" alt="">
                
              </label>
        <input 
          type="number" 
          id="number" 
          name="age" 
          min="10"
          max="99"
          class="form-control"
          placeholder="Age" required>
              
              </div>
      <div class="group-form">
        <p>Which option best describes your current role?<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmQPY6uzN1zl0-bNw7kcR46wqcbB0VnmB3Cw&usqp=CAU"></p>
        <select id="dropdown" name="role" class="form-control" required>
          <option disabled selected value>Select current role</option>
          <option value="student">Student</option>
          <option value="job">Full Time Job</option>
          <option value="learner">Full Time Learner</option>
          <option value="preferNO">Prefer not to say</option>
          <option value="other">Other</option>
        </select>
        </div>
      <div class="group-form">
        <p>Would you recommend freeCodeCamp to a friend?</p>
        <label><img src="https://img1.freepng.ru/20180204/qoq/kisspng-arrow-button-icon-right-arrow-transparent-background-5a77bc2a39d211.9125852015177963942368.jpg">
        <input name="user-recommend" 
          value="definitely" 
          type="radio" 
          class="input-radio" checked>
          Definitely
      </label>
        
         <label><img src="https://img1.freepng.ru/20180204/qoq/kisspng-arrow-button-icon-right-arrow-transparent-background-5a77bc2a39d211.9125852015177963942368.jpg">
        <input name="user-recommend" 
          value="maybe" 
          type="radio" 
          class="input-radio" checked>
          Maybe
      </label>
        
         <label><img src="https://img1.freepng.ru/20180204/qoq/kisspng-arrow-button-icon-right-arrow-transparent-background-5a77bc2a39d211.9125852015177963942368.jpg">
        <input name="user-recommend" 
          value="Not-sure" 
          type="radio" 
          class="input-radio" checked>
          Not sure
      </label>
        
        
      </div>
      
       <div class="group-form">
          
        <p>What is your favorite feature of freeCodeCamp?<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmQPY6uzN1zl0-bNw7kcR46wqcbB0VnmB3Cw&usqp=CAU">
          
        </p>
        <select id="dropdown" name="role" class="form-control" required>
          
          <option disabled selected value>Select an option</option>
          <option value="сhallenges">Challenges</option>
          <option value="projects">Projects</option>
          <option value="community">Community</option>
          <option value="openSource">Open Source</option>
          
        </select>
         
        </div>
      
        <div class="group-form">
          <p>What would you like to see improved?</p>
          
          <label><input
          name="prefer"
          value="front-end-projects"
          type="checkbox"
          class="input-checkbox">Front-end Projects
          </label>
          
      <label>
        <input
          name="prefer"
          value="back-end-projects"
          type="checkbox"
          class="input-checkbox">Back-end Projects
      </label>
          
      <label><input
          name="prefer"
          value="data-visualization"
          type="checkbox"
          class="input-checkbox"
        />Data Visualization</label
      >
      <label
        ><input
          name="prefer"
          value="challenges"
          type="checkbox"
          class="input-checkbox">Challenges</label>
          
      <label><input
          name="prefer"
          value="open-source-community"
          type="checkbox"
          class="input-checkbox">Open Source Community
          </label>
          
      <label><input
          name="prefer"
          value="gitter-help-rooms"
          type="checkbox"
          class="input-checkbox">Gitter help rooms
       </label>
          
      <label><input
          name="prefer"
          value="videos"
          type="checkbox"
          class="input-checkbox">Videos</label>
          
      <label><input
          name="prefer"
          value="city-meetups"
          type="checkbox"
          class="input-checkbox">City Meetups</label>
          
      <label><input
          name="prefer"
          value="wiki"
          type="checkbox"
          class="input-checkbox">
        Wiki</label>
      <label><input
          name="prefer"
          value="forum"
          type="checkbox"
          class="input-checkbox"
        >Forum</label>
      <label>
        <input
          name="prefer"
          value="additional-courses"
          type="checkbox"
          class="input-checkbox"
        >Additional Courses</label>
        </div>
      <div class="group-form">
  
        <p>Any comments or suggestions?</p>
        
       <textarea
        id="comments"
        class="input-textarea"
        name="comment"
        placeholder="Enter your comment here...">
       </textarea>
        
      </div>
      
      <div class="group-form">
        <button 
        type="submit" 
        id="submit" 
        class="submit-button">
        <b>Submit</b></button>
      </div>
    </form>
    </div> 
  </body>
  
</html>
