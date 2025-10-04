<!-- this is my first html code ever and I am learning -->

<!DOCTYPE html>
<html lang="en">

<!--The following alows me to name the tab that this file creates be named what I want-->    
<head>
    <title>html journey   </title>
</head>



<!-- the folloing is code i learned before project 1-->
    <body>
    
    <h1> I can type anything I want in here and it will show up in the body of my webpage</h1>
    
    <!--this attribute gives the immage a link to hte bottom of the paged given the href-->
    <a href="#bottom">
    <img src="https://platform.polygon.com/wp-content/uploads/sites/2/chorus/uploads/chorus_asset/file/136146/CwTMhsN.0.gif" alt=""/>
    </a>

    <!-- This attribute gives the pikachu image the ability to open a new tab to a youtube video-->
    <a href="https://youtu.be/Aq5WXmQQooo?si=1xeaAxtlJ9-lUnYH" target="_blank" >
    <img src="https://i.scdn.co/image/ab67616d0000b273cfeae645958e9248abff0710" alt=""/>
    </a>




    


<!-- This div divedes the rest of the code into this one project, id gives this section an identitifccation, in this case this is hte bottom of the body of this code. -->
    <div id="bottom">
        <p>This is the bottom of the page</p>
    </div>

    
    </body>



<!-- the following will be code learned before project 2-->
<body>

<div id="table">   
<table border="10">
    <tr bgcolor="red">
        <!-- this blank is just to align the table,
         scope takes the calue of eaither col or row to verify that the table heading is what it is.
         then there is colspan and rowspan which allow the table to have a cell that spans multiple columns or rows.
        
        -->
        <thead>
        <th></th> 
        <th scope="col">colum number 1</th>
        <th scope="col"> colum number 2</th>
        </thead>
    </tr>

    <tbody> 
    <tr> 
        <th scope="row"> row number 1</th>
        <td> data 1</td>
        <td> data 2</td>

    </tr> 
    </tbody>
</table>
</div> 



</body>
