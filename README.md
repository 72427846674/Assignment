<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Movie review">
    <meta name="author" content="Sahar Timori">

  <title>Movie review</title>
</head>
<body>
    <header>
        <h1>Movie Reviews Central</h1>
        <nav>
            <ul>
                <li>
                    <a href="#">Latest Reviews</a>
                </li>
                <li>
                    <a href="#">Top Rated</a>
                </li>
                <li>
                    <a href="contact us.html">Contact Us</a>
                </li>
                <li>
                    <a href="#">About Us</a>
                </li>
            </ul>
        </nav>
    </header>
   
    <section id="Latest Reviews">
        <h1>Latest Reviews</h1>
        <h4>Pirates Of The Caribbean</h4>
        <img src="jack img.jpg" alt="poster">
        <img src="jack img 2.jpg" alt="poster">
        
      </section>
      
    <section id="summary">
        <article><p>Capt. Jack Sparrow (Johnny Depp) arrives at Port Royal in the Caribbean without a ship or crew.<br>
            His timing is inopportune, however, because later that evening the town is besieged by a pirate ship.<br>
             The pirates kidnap the governor's daughter, Elizabeth (Keira Knightley),<br>
              who's in possession of a valuable coin that is linked to a curse that has transformed the pirates into the undead.<br>
            A gallant blacksmith (Orlando Bloom) in love with Elizabeth allies with Sparrow in pursuit of the pirates.</p>
        </article>
    </section>

    <section id="movie">
        <video width="320" height="240" controls>
        <source src="short.MP4" type="video/Mp4">
        Your browser does not support the video tag
        </video>
        <a href="https://youtu.be/UD_87XxocRE">full movie</a>
    </section>

    <section id="Top Rated">
        <h1>Top Rated Movies</h1>
        <table>
            <tr>
                <th>Rank</th>
                <th>Title</th>
                <th>Year</th>
                <th>Rating</th>
                <th>Genre</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Pirates of the Caribbean</td>
                <td>2007</td>
                <td>&#9733; &#9733; &#9733; &#9733; &#9733;</td>
                <td>Action</td>
            </tr>
        </table>
    </section>

    <aside>
        <ul>
            <li>
                <a href="https://youtu.be/7iGgiWuguhY">Upcoming movies</a>
            </li>
            <li>
                <a href="https://youtu.be/8ouGzGn5LvI">Interviews With Directors</a>
            </li>
        </ul>
    </aside>

 <section id="content form">
    <form action="" method="post">
        <h1>Contact Us</h1>

        <label for="M">Name:</label>
        <input id="M" type="text" name="movie"><br>

        <label for="O">Email:</label>
        <input id="O" type="email" name="movie2"><br>

        <label for="oo">Favorite Movie Gener:</label>
        <select name="Movie6" id="oo">
            <option value="Item1">Action</option>
            <option value="Item2">Drama</option>
            <option value="Item3">Comedy</option>
            <option value="Item4">Adventure</option>
            <option value="Item5">Westren</option>
            <option value="Item6">Fiction</option>
            <option value="Item7">Narrative</option>
        </select><br>

        <label for="i">Message:</label>
        <textarea id="i" name="Message" rows="2" cols="30"></textarea> <br>

        <input id="che" type="checkbox" name="movie4">   
        <label for="che">Subscribe to newsletter</label><br>

        <input type="submit" name="movie5" value="send">
    </form>
 </section>

 <footer>
    &#169; 2024 Movie Review Central
 </footer>
    
</body>
</html>
