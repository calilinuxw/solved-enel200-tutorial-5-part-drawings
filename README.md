Download Link: https://assignmentchef.com/product/solved-enel200-tutorial-5-part-drawings
<br>
<strong>   Part Drawings </strong>

We’ve seen when the car body was modelled that two dimensional sketches can be used as an input for generating three dimensional models. Working with such three dimensional models provides a great environment for resolving designs, checking the fit and behaviour or assemblies, and communicating conceptual and aesthetic design information with other people. At some point however it is likely that we want to manufacture our product, and for this we must move our part models back into the two dimensional arena by creating part detail drawings.

<h1>Goals</h1>

<ul>

 <li>Understand the role of part detail drawings</li>

 <li>Know how to create drawing files</li>

 <li>Be able to lay out a drawing in a considered way</li>

 <li>Be able to apply appropriate part dimensions</li>

</ul>




<h1>Exercise 1:           Front Cover</h1>

The first part we’ll create a detail drawing for is the front cover part. The drawing is relatively simple, but the principles shown are important and apply regardless of the drawing complexity.

Each drawing is a separate SolidWorks file which is created by selecting New from the File main menu.




As is the case for parts and assemblies there are many settings that can be changed to suit the user preference or the standard that the individual or company are working to. Select the UC Drawing Template so that the drawing environment will be set up in the same way as the examples.




Each drawing file that you open can have as many sheets as you like, and indeed sometimes a part drawing will require more than one sheet. You <em>could</em> also include multiple parts on a drawing sheet, or even have multiple parts detailed in one drawing file, each on separate sheets. However this is not the intended or correct use of drawing files. <strong><em>You should only detail one part per drawing file, so for each part create a new drawing file</em></strong>. The reasons for this are as follows:

<ol>

 <li>Once the parts are being manufactured you may at some point be outsourcing production of one or more parts. It will be confusing, and undesirable from a confidentiality viewpoint, to send drawing to a particular supplier that is going to manufacture Part B if the drawing also contains details for Part A and C.</li>

 <li>Usually drawings are identified by a drawing number, and that number is the same as the part number which it details. This system breaks down if multiple parts are detailed on the same drawing.</li>

 <li>When a part is modified it is usual practice to update the drawing and release it as a new revision. If multiple parts are detailed on the drawing the revision system will break down because some parts on a drawing will have a new drawing revision (because one of the parts changed) but they are unchanged.</li>

 <li>Drawing title blocks are designed to address information such as material and tolerances to a particular part. This becomes nonsense if there are multiple parts on the drawing.</li>

</ol>




Drawing sheet layouts vary between different organisations to suit their exact requirements and preferences, but the information contained is reasonably consistent. We’ll have a closer look at the information contained in the UC drawing sheet.




<ol>

 <li><strong>Title Block</strong>. This contains a range of information including:

  <ul>

   <li>Identification of the organisation that created or owns the drawing</li>

   <li>Drawing title</li>

   <li>Drawing number</li>

   <li>When and by whom the drawing was created</li>

   <li>The material the part is made from</li>

   <li>General tolerances for dimensions shown</li>

  </ul></li>

 <li><strong>Revision Table</strong>. When a part is changes there needs to be a new revision of the drawing released to communicate what the changes are. The revision table provides a basic history</li>

</ol>

for what revisions have been made, what the changes were, when they were done and by whom.

<ol start="3">

 <li><strong>General Notes</strong>. Here we can put notes that relate to the part itself or how the drawing should be interpreted.</li>

</ol>

The Revision Table and the General Notes can be edited manually by double clicking on the text and changing or adding to what is there by default.

To add additional rows to the Revision Table right click on the table and select Add Revision from the Revisions popup menu.




Changes to the Title Block are not so obvious, but are done in a way that is very useful. All of the information that goes into this area originates from the part that is shown on the sheet. Because part drawings, assemblies, and assembly drawings are all downstream uses of parts it makes good sense to have all the information about the part stored in the part file itself so it can be propagated downstream. The alternative would be that you would have to manually enter data as required each time you used the part, which is a wasteful and error prone process.

The part information can be entered or updated in the part either before it is inserted into a drawing, or it can be done afterwards, but in either case it is in the part file it is entered and not in the drawing file. In this example we’ll edit the information in the part first, and then we’ll see that when we insert a view of this part on the drawing the data will automatically appear in the title block.

<em>Natural</em>. The Number property refers to the part number shown on the drawing and should not be altered in the table. The data string that is there by default will cause the drawing number to be displayed as the name of the part file, and usually this would be the part number (although not in our example). The Part Description should be something descriptive but succinct, so for this example we will use <em>Engine Front Cover</em>.

Once complete click on the OK button, and then browse in the Window main menu for the drawing file you have created and click on it to return to it. Because it has not been saved with a name yet it will likely appear in the list as <em>Draw1 – Sheet1</em>.

To begin the drawing itself click on Model View in the View Layout tab of the Command Manager. As the name implies, this will allow us to select the model that we want to create views of. Unlike with paper based or 2D CAD software, we do not need to draw views of the part as such, we simply need to indicate the orientation and location of the views and SolidWorks takes care of creating it.




The Model View dialogue opens in the Feature Manager area, and works in a similar way as for inserting a part into an assembly. Suitable files (parts or assemblies) that are already open in the current SolidWorks session are shown in the Open Documents list, and the browse button is used if you want to use a file that isn’t currently open.

We already have the front cover part open in this session, so select this by double clicking on this in the Open Documents selection box, or clicking the right facing arrow in the top right corner of the Model View dialogue.




The dialogue enters the second stage, in which it wants to know the orientation and location of the first view. By default the first view is set as the Front view of the part, which means that the Front plane of the part model will be in the plane of the drawing sheet. It follows from this that the default orientation depends entirely on the orientation that you chose to model the part in, but in any case is not really of much importance as the view orientation can easily be changed at any time. To begin with click in the graphics area to specify the location of the view and then click on the green tick to accept it regardless of the orientation.

The view we actually want is as shown in the example below. If yours doesn’t look like this you can change the view orientation by clicking anywhere on the view or the border around the view (highlighted dotted green) to open the Drawing View dialogue once again. Different standard views are selected by clicking on the icons within the red box indicated below. Try different views until you get the one to match the example.




For this component we decide to have two orthographic views, the one already created, and one which will sit to the right of this. Later we will also add a shaded pictorial view.

Select Projected View from the View Layout tab of the Command Manager and then click to the right side of the first view in the Graphics Area. The projected view that will be created is determined by where on the screen you click with respect to the view that is already on the sheet. Because we click out to the right of the first view we will get a view as if it were looking at the first view of the part from the right hand side.

The two projected views should now look as shown. Note that the order in which you create the views has an impact on some of their behaviour. The first view is the parent and the others are child views. Experiment by trying to move both of them and you will see that the first (parent) view can move anywhere, but the second (child) view can only move horizontally so it stays in line with the parent view.

The last view we will create for this drawing is a pictorial isometric view, and we will base this off the second of the orthogonal views we have already. Create this in a similar way to how you created the previous view, by selecting the Projected View tool from the View Layout tab of the Command Manager. Previously, because there was only one view on the drawing, SolidWorks made the necessary assumption that it was that view we would project a new view from. This time we have two views, so you are prompted to select the view to project from. Click in the Graphics Area over the right side view and then move the pointer around it to see the different projection options that are offered. We want the view that is created when the pointer is in the top right quadrant around the right side view. Click in this location to create the view and then accept and exit the Projected View tool by clicking the green tick.




The drawing sheet should now look something like as shown in the example, but your views may be in a different location. Obviously the isometric view is not in a good location here, so if yours is similar you can click on the border of the view and move it to a better position. Unlike orthogonal projected views, the isometric view does not need to stay aligned with its parent view.




When you click on the view border, or the view itself, you can see that the Drawing View dialogue appears in the Feature Manager area. This contains a number of parameter controls, including for the Display Style and Scale.

Experiment with the different Display Style settings by clicking on each to see the effect on the view. The shaded view with outlines is the one we want, as this gives a view that can be unambiguously understood the easiest.

By default a view will have the same scale as its parent (the view it was projected from). As a general rule the shaded views appear too dominant on the sheet when they are the same scale as the line views, so select the Use Custom Scale option and from the dropdown menu select User Defined. Enter in a smaller scale than the line view, in this case 3:2 is appropriate. The scale value can either be entered as a ratio (3:2) or a fraction (3/2).




At this point it’s important to reflect on what we have done so far and be more explicit about what we have done and <em>why</em> we have done it. The process we have just worked through is called the <em>drawing layout</em>, and is <strong>absolutely critical for producing a good drawing</strong>. Let’s break the drawing layout process into the key decisions, and list out the criteria for making these.

The drawing layout process:

<ol>

 <li>What views will be shown on the drawing?

  <ul>

   <li>Show the minimum number of orthogonal views so that all features on the part can be dimensioned. In this case we chose only two views because these are sufficient to completely dimension the part. Don’t think that adding more views is playing it safe – unnecessary views spoil a drawing.</li>

   <li>Remember that sections and partial sections (covered later) can be used to show ‘inside’ a part, which can sometimes reduce the number of views that are required.</li>

  </ul></li>

</ol>

Fewer views usually results in a drawing that is easier to interpret.

<ul>

 <li>Only use hidden detail in the drawing views if really necessary – sections are nearly always more appropriate. Hidden detail usually complicates the drawing and makes it difficult to read.</li>

 <li>Include a shaded isometric view in the top right corner that shows the part at an angle which displays the important part geometry best, or an angle which explains some geometry which otherwise might be difficult or ambiguous to understand from the line views. This view color (set in the part) should preferably be a light grey, but in any case certainly not a dark color – it must be clear when printed.</li>

</ul>




<ol start="2">

 <li>How big should the views be?

  <ul>

   <li>Just like the story of the three beers, there is a too big, a too small, and a just right. SolidWorks has a guess at the view scale for you when you place the first view on the sheet, but sometimes this will need to be modified depending on how many views you decide are necessary.</li>

   <li>The drawing views should fill the drawing area, but have a reasonable amount of ‘white space’ between the views and the border. Another way of saying this is that the views should be as large as possible without making it look as though they are a tight fit on the sheet.</li>

   <li>This shaded view should not be too dominant on the sheet, so change the scale of it so it is about 2/3 the scale of the main drawing views.</li>

  </ul></li>

</ol>




<ol start="3">

 <li>Where should the views be?

  <ul>

   <li>Place the shaded view in the top right, so there is a small and even space above it and to its right.</li>

   <li>The main views, however many are needed, should be placed so as a group they are centralised in the remaining space on the sheet. Don’t attempt to centralise them on the sheet as a whole, and don’t have them offset vertically or horizontally so there is much more space on any side than the others.</li>

  </ul></li>

</ol>

With the drawing layout looking good, it’s time to get some details onto the drawing. Centre lines and symmetry lines are used on views are important:

<strong>Centre lines</strong>: apply wherever there is an axis of revolution for a feature. This adds critical information to a drawing. For example, a side view of a cylinder appears as a rectangle rather than a cylinder if the centre line is not included.

<strong>Symmetry lines</strong>: apply whenever there is symmetry in the part, indicating to the reader that whatever dimensions apply on one half also apply on the other half.

By default SolidWorks applies crosshairs (end view centrelines) on circular features, but not side view centrelines. To add these select the Centerline tool from the Annotations tab of the Command Manager.

On the right hand view select either the cylindrical feature, or the top and bottom lines (shown green in the example) which represent the cylindrical feature. Either selection will create a centreline for the feature. Click the green tick to exit the Centreline tool.

Because this centreline is also a line of symmetry we want the centreline to extend right through the part. Any centreline can have its length modified by clicking on it in the graphics area and then dragging the dot which appears on either end of it.

Now to apply dimensions onto the part, which is perhaps the most difficult drawing step for students that are new to drafting. The key is to decide what dimensions are required on the drawing, as a drawing with insufficient or redundant dimensions is either useless or misleading. A useful guide for making this decision is as follows:

<strong>Even though you are selecting lines on the screen to apply dimensions, remember that it is the <u>features these lines represent</u> which you are dimensioning, not just distance between any lines. </strong>

What does this mean in our example? We have the following features:

<ul>

 <li>Long cylinder</li>

 <li>Square flange</li>

 <li>Short cylinder</li>

 <li>Big hole through whole part</li>

 <li>Small holes through square flange</li>

 <li>Some fillets</li>

</ul>

We need to make sure that there are enough dimensions to specify the <strong><em>size</em></strong> and <strong><em>position</em></strong> of all of these features, and then with the addition of some overall dimensions (for quick part size reference), the dimensioning is complete.




The display of radii and diameters can be customised in a number of ways to suit the drawing you are working on. In this example the default display has been changed to that the arrow only points to one side of the circle, and the text is displayed horizontally. After placing the dimension, select it again in the graphics area and the Dimension dialogue will appear in the Feature Manager area. On the Leaders tab of the Dimension dialogue click on the options shown in the example to see the difference. Experiment with some of the other options also to see what effect they have – they will update in the Graphics Area as you select them.

The square holes have a diameter (size), but unlike the other features so far we also need to apply dimensions for the position of them.

For the position of the holes we choose to apply two 30mm dimensions giving the width and the height between them. This is sufficient because of the cross hair centrelines of the part, which also act as lines of symmetry. Because of this symmetry an engineer knows that the 30mm dimension must mean that the holes are positioned 15mm each side of the part centreline.

We don’t have to give any angles for the position because they look to be horizontally and vertically aligned in a square pattern. In the language of engineering drawings if a feature looks to be perpendicular or parallel to another feature, and it is not dimensioned otherwise, then it is assumed to be so.

Because we didn’t have enough space for the 30mm dimensions the 40mm dimensions have been moved outwards to make room. Dimensions can be moved by clicking on them and dragging with the mouse button held down. Note that consistent spacing has been maintained between the part and the dimensions, and between the dimensions themselves.




All four of the small holes are the same diameter but rather than applying a dimension to all of them we have put a dimension on just one of them with the text “4 x” in front of the diameter dimension. To the reader this means the dimensions is relevant for four similar features, and these are readily identified as the small holes.

The “4 x” text is typed into the Dimension Text box on the Value tab of the Dimension dialogue. Don’t change the &lt;MOD-DIAM&gt;&lt;DIM&gt; text that is already there, as these are the codes which will have SolidWorks display the diameter symbol and the actual diameter value.




The last features to dimension are the fillets. The

R5.0 corner on the square flange feature doesn’t need repeating on the other corners because the symmetry lines imply that it is.

Note that all the radii are positioned so they appear in a similar way, along the bottom of the part, at the same angle, and with similar dimension line length. This will vary from drawing to drawing of course, but the general principle is to <strong>try and achieve a neat drawing through consistency of spacing, alignment and orientation</strong>.

To complete the dimensioning apply the overall dimensions for the part. The width and height are already shown (both 40mm), so we are just left with applying the overall length (41mm). Overall dimension are required on all parts, as they give a quick reference of the size of the part. In our

example the overall length can be calculated from the dimensions already there (6+5+30=41), so we have added brackets around the 41 dimension. These brackets define the dimension as a <em>reference</em> dimension, or in other words a dimension that is otherwise already available on the drawing, but it is given again for convenience of the reader. Reference dimensions are not used for manufacturing, do not have tolerances applied to them, and are ignored by manufacturing quality control inspectors.

The part drawing is now complete. While other drawings will vary in the details, remember that the principles of how this drawing layout and dimensioning scheme were designed can be used regardless. <strong>Diligently applying the same steps and thought process that have gone into this drawing will provide a good result for all of your part drawings</strong>.

<h1>Exercise 2:          Section Views</h1>

Sometimes a part has internal features which are impossible to show in standard drawing views regardless of how many views are shown. Also at times, even if it is possible to show a feature in standard views, it would make a drawing easier to understand if we could show inside the part as if it had been cut. In these situations we use <em>section views</em>.

For this example we will complete a drawing of the engine piston so that we can show the shape inside it. Initially we have done a drawing that applies the layout principles learned in the first exercise, but it is apparent that the inside geometry of the part cannot be shown.

Note: if the piston is upside down when you first insert the view onto the drawing you can rotate it using the rotate tool in the head up menu. You can use this

We decide that a section view replacing the right hand view would solve this problem, so select the right view and delete it (click on the view and press keyboard delete key).

To create the new section view, select the Section View tool from the View Layout tab of the Command Manager.

This tool needs a sketch line to show where an existing view will be cut and projected to create the section view, and SolidWorks immediately provides you with a line sketching tool so you can draw this. In our case we want to draw a vertical line on the piston that passes right down the middle of it (through the centre of the hole).

A section line through the left view and the label below the section view are automatically created.

The remainder of the drawing can now be completed just as was done in the first exercise. The features of this part are:

<ul>

 <li>A cylinder</li>

 <li>Hole through cylinder</li>

 <li>A cylindrical cut-out within the first cylinder</li>

 <li>Fillet</li>

</ul>

Check the sizes of each of these features are fully defined by dimensions. Also check if there are any features that require their position to be defined. In this case the only position requirement is the height of the through hole, which is dimensioned from the bottom of the piston.

No top view is required in this drawing as it is obvious from both the pictorial view, together with the diameter dimension of the piston, that it is a circular cylinder shape. Adding a top view would not provide any more information so it should not be included.

The position of the through hole only needs the height defined, and not the left/right position (on the left view), because it <em>looks</em> like it is sitting on the centre line of the part. As before if something on an engineering drawing looks to be so, and is not dimensioned otherwise, then it is interpreted as being so.

<strong>   </strong>Exercise 3:           Crankshaft Part Drawing

Complete a part drawing of the engine crankshaft.

Exercise 4:           Cylinder Block Part Drawing

Complete a part drawing of the engine cylinder block. While not strictly necessary for this part, provide a cross section through the part to show the cylinder bore profile.


