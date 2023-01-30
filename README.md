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
?>```