# SecureX
<br>
K9 revolutionises the finding of a missing person by efficiently and accurately identifying individuals in surveillance footage, social media, and other digital sources. By comparing the victim’s image to a database of images, officials can quickly track a missing person's movement over time by identifying them in multiple images captured at different locations and creating a predictive route map. Furthermore, the app also track down possible suspects by identifying people who may have been in contact with the victim from the feed.
<br>
## Steps of Algorithm:
<ul>
  <li>We provide the system with an image of the missing person. The algorithm processes the input through web/social media(API’s & web scraping) and live camera feeds.</li>
  <li>The system detects the faces using YOLO (CNN).</li>
  <li>Detected faces are compared using face_recogntion library.</li>
  <li>If similarity is found, it extracts the username, location, time/date, tagged people, etc. from social media and live camera feeds.</li>
  <li>Alerts the authorities concerned via mail (smtp lib) or a popup message.</li>
  <li>predicted route map is generated.</li>
</ul>
<img width="1145" alt="Screenshot 2023-12-31 at 9 10 36 PM" src="https://github.com/SATVIK2610/SecureX/assets/88959905/dbf435dd-1f68-4c52-a453-63e4dfc306db">

## OPPORTUNITIES
The existing softwares are either too complex to be implemented or are less accurate.
K9 will automate the investigation process to large extent. Thus have a wider opportunity for revolutionising the conventional methods.
K9 ensures :
<ul>
  <li>High accuracy output : Training with new data, which helps it to learn over time</li>
  <li>Fast computing Algorithm : Speeding up the investigation by automating the process, real time monitoring and generating leads for investigation</li>
  <li>Efficient data management : Organising the data , make it quickly retrievable, protect it from unauthorized access and ensure data privacy</li>
</ul>

##Features
<ul>
  <li>Well Designed UI</li>
  <li>Built-in Integration</li>
  <li>High Accuracy</li>
  <li>Fast Processing</li>
  <li>Data Privacy & Security</li>
</ul>

##Tech Stack
<ul>
  <li>Tkinter</li>
  <li>OpenCV</li>
  <li>MySQL</li>
</ul>
