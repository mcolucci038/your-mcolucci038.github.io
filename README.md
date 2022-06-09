<div class="main">
    <h1 id="title">Cool Survey form</h1>
  <p id="desciption">
      Answer and fill out these questions to see how cool you are!
  </p>
  
  <div class="main-content">
      <div class="main-content">
          <form id="survey-form">
              
              <label for="name" id="name-label">Name</label>
              <input id="name" type="text" required placeholder="Enter your name" />
              
              <label for="email" id="email-label">Email</label>
              <input id="email" type="email" required placeholder="Enter your email" />
              <label for="number" id="number-label">Enter your rate from 1 to 10</label>
              <input id="number" type="number" min="1" max="10" required placeholder="Enter your rate" />  
              
              <label for="dropdown">Which option best describes your current role?</label>
           <select id="dropdown">
               <option value="studen">Student</option>
               <option value="full-time-learner">Full time learner</option>
               <option value="full-time-job">Full time job</option>
               <option value="prefer-not-to-say">Prefer not to say</option>
               <option value="other">Other</option>
              </select>
              
              <fieldset>
                  <legend> Would you recommend my channel to a friend?</legend>
                  
                  <input type="radio" name="recommend" checked id="definietly" value="definitely" /><label for="definitely">Definitely</label><br />
                  
                  <input type="radio" name="recommend" id="maybe" value="maybe" /><label for="maybe">Maybe</label><br />
                  
                  <input type="radio" name="recommend" id="not-sure" value="not-sure" /><label for="not-sure">Not sure</label><br />
              </fieldset>
              
              <p>What would you like to see improved?</p>
              <input type="checkbox" id="video-length" name="video-length" value="video-length">
              <label for="video-length">Video Length</label><br>
              <input type="checkbox" id="content-quality" name="content-quality" value="content-quality">
              <label for="content-quality">Content quality</label><br>
              <input type="checkbox" id="more-video" name="more-video" value="more-video">
              <label for="more videos">Add more videos</label><br>
              
              <label for="comment">Any comments or suggestions?</label>
              <textarea rows="4" cols="50" id="comment">Enter your comment here...</textarea>
              
              <button type="submit" id="submit">Submit</button>
              
          </form>
      </div>
    </div>
   </div>
