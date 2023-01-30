# Wout blomme
## Soccer

I used to play a lot of **soccer** when I was little. So thats why I **like it**.

--------
## Favorite Team
### The Red Devils (Belgian National Team)

1. Eden Hazard
2. Kevin Debruyne
3. Romelu Lukaku

* Club Brugge
* Anderlecht
* Cercle Brugge

[About Me Markdownfile](AboutMe.md)


------
## Countries I recommend

In the next table I put some countries I recommend visiting.

Name | Reason | Days
--- | --- | ---
Spain | Its hot | 7 days
Belgium | its beautiful | 5 days
Austria | its fun skiing | 7 days
Morocco | its hot | 7 days

-------
## funny quotes

> I'm not superstitious i am a little stitious
> _Michael Scott (The office)_

> Someone asked me, if I were stranded on a desert island what book would I bring: How to Build a Boat.
> _Steven Wright_

-------
## Code Snippet

> I am working on a WordPress site that uses a gravity form. The gravity form has 20 questions, after a user fills it out they press submit and then a page loads saying the form has been submitted. The form submits to an AWS API that checks the form and returns a percent correct to the gravity form inside the admin panel. I am trying to get that result to display on the website so that the user can see. I don't know how to get the response. When i try to access the AWS endpoint through curl or postman, I get forbidden errors. I am using the endpoint and the API key listed in the gravity forms settings

[Click Me for stackoverflow question](https://stackoverflow.com/questions/75288759/wordpress-gravity-form-response-issue)


```WordPress
<h3>All Post Meta</h3>

<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>
```