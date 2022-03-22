# Team-16
Team 16  Web Simulator (2)

>> # specification：  
>>
>> Automation in your project board does not apply to archived project board cards. For example, if you close an issue in a project board's archive, the archived
>> card does not automatically move to the "Done" column. When you restore a card from the project board archive, the card will return to the column where it was
>> archived.

![chatbot](https://media.istockphoto.com/vectors/chatbot-icon-with-virtual-support-service-bot-or-online-artificial-vector-id1147779501?k=6&m=1147779501&s=170667a&w=0&h=AvPUGdTXb_kMXEzeJMGb_RlyQJDkS1tnbqpCPUHbNfA= "Magic Gardens")

# The group leader on duty：
The coordinator Bichuan Zuo
Week2~3 __Bichuan Zuo__. 

Week4~5 __Pengcheng Wang__. 

Week6~7 __Bangfu Yan__. 

Week8~9 __Jiansong Feng__. 

Week10~Week11 __Testing& Review or Add new features__

Week12  __assessment__（ group&individual ）. 


Records: [1st. meeting with clients](https://uao365-my.sharepoint.com/:v:/g/personal/a1790344_adelaide_edu_au/EZjgeZyx-V9Ov5_0ZdX7hvkB8F0ZdyNWcnkfnyLrv9D2sw?e=DGkvDE)

Gantt Chart:

````mermaid
gantt
    dateFormat  MM-DD
    title       WEB SIMULATOR
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section 2nd week
    1st meeting with clients           :done,  des1, 03-09, 0d
    follow-up meeting                   :done,  des2, 03-12, 3d
    research background                 :done,  des3, after des2, 5d
    choice for tech-stack               :done,  des4, after des3, 5d

    section 3rd week
    prepare for meeting                 :crit, done,b1, 03-14,2d
    headless browser                    :crit, done,b2, after b1, 2d
    meeting with the other team         :crit, done,b3, 3d
    2nd meeting with client             :crit, done,b4, 03-16,0d
    set a simple demo individually      :done, b5,2d
    pitch presentation                  :milestone, 04-01, 0d

    section 4th week
    Q&A discussion                      :active, c1,03-22, 0d
    3rd meeting                         :active, c2,03-23, 20h
    follow-up meeting                   :active, c3, after c2 , 48h
    add functionality for scroll-up     :c4,after c3,7d
    prepare for pitch presentation      :crit,active,c5,after c3,5d

    section 5th week 
    pitch presentation                  :d1,03-28, 3d
    test                                :d2,after c4,20h
    Add fuction to demo page                    :d3,after c5, 48h
    
    section 6th week 
    set prototype:                      :e1,03-28, 3d
    click&scroll with sub-act           :e2,after c4,20h
    link to object:                     :e3, 48h
    milestone1                          :milestone, after e3, 0d
    
    section 7th week 
    click&scroll&key                    :f1, after e3, 3d
    test                                :f2, after f1,2d
    Add to demo page                    :f3, after f2,48h
    
    section 8th week 
    Update any issue or bug             :g1, after f3, 3d
    test with the other team:           :g2, after g1, 20h
    report to clients                   :g3, after g2, 48h
    
    section 9th week 
    add function to find object by cooridnate  :h1, after g3, 5d
    test                                       :h2, after h1,20h
    test for return to the scrap team          :h3, after h2, 12h
    
    section 10th week 
    Finalise the project                :i1, after h3, 7d
    documention                         :i2, after i1, 7d
    1st demo                            :i3, after i2, 48h
    
    section 11-12th week
    perfect UI&UX                : j1, after i3, 7d
    add extra function to improve: j2, after j1,5d
    final presention             : j3, after j2, 3d
    final report                 : j4,after j2,3d
     

````

