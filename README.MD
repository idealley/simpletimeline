# Simple Timeline

[See the timeline](https://www.ersnet.org/congress-and-events/events-calendar) in production

Clone this repo:
```
    $ git clone https://github.com/idealley/simpletimeline.git
```

Use a similar html structure

```
                <div class="timeline">                
                    <ul>
                        <li class="event">  
                            <div class="card-container">
                                <div class="card card-event"> 
                                </div>
                            </div>    
                        </li>
                    </ul>
                </div>
```
Commpile the less file with your tool of choice (e.g. gulp) Be aware that @phone, @tablet and @primary-color are Bootstrap 3.x variables

Include the `timeline.js` at the bottom of your page and the `timeline.css` in the head
