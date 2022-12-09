# ***ANASTASIYA VORONOVA***
* * * * 
# **Contact information:**
Phone: +375 29 2174433
E-mail: buchneva.anastasya92@gmail.com
Telegram: @nastabu
[LinkedIn](http://linkedin.com/in/настя-бучнева-335b94242)
****************************************
# **About me:**

Self-organized with a high sense of responsibility customs declarant with 6
years of experience and multitasking meticulous head of logistics with about 1 year
of experience.

* As a customs declarant I used to do all possible work related to the
customs clearance , including certification, contracts, logistics, warehousing,
legislation.
* As a head of logistics I was in charge of arranging successfully functioning
Free Customs Zone and warehouse operations for the electric bus assembly.
# **Skills**
 * OOP Basics
 * C# Basics
 * Git,GitHub
 * VS
 * Unity 2D Basics

# **Code examples**
``` 
    #region Unity methods

    /// <summary>
    /// Start is called before the first frame update
    /// </summary>	
    public void Start()
    {
       
        // set position of game object for autograder
        transform.position = new Vector3(-2.5f, 0, 0);

        // add and run the timer

        directionTimer = gameObject.AddComponent<Timer>();
        directionTimer.Duration = TimerDuration;
        DirectionTimer.Run();



    }

    /// <summary>
	/// Update is called once per frame
	/// </summary>	
    public void Update()
    {
        // change direction as appropriate
        if (directionTimer.Finished)
        {
            directionMultiplier *= -1;
            directionTimer.Run();
        }

        // move game object
       

        Vector3 move = transform.position;
        move+= new Vector3(directionMultiplier*MoveAmountPerSecond*Time.deltaTime, 0, 0);

        transform.position = move;
    }

    #endregion 
```

# **Courses**

* RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
* JavaScript Manual on learnjavascript.ru (in progress)
* .NET Development EPAM (self-study)
* Specialization C# Programming for Unity Game Development (in progress, 3 of 4 courses completed)
![Certificate](/assets/Certificate.png)

# **Languages**

* English - B2
* German - B2

 




