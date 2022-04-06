# First-Webpage
Final project for SheCodes Coding Workshop
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Poisonous Plants: Oleander</title>
    
    <style>

      div{
     display: block;
      }
      
      body {
        background-color:#283739; 
      }
         h1 {
        text-align:center;
        font-family: Bookman, URW Bookman L, serif;
      }
      h2 {
          text-align: center;
          font-family:Georgia, serif;
      }
      h3 {
          text-align: center;
          font-family:Georgia, 'Times New Roman', Times, serif;
          line-height:0cm;
      }
      p{
          text-align: justify;
          border-radius: 15px;
          font-family: Georgia, 'Times New Roman', Times, serif;
          font-size:large;
          font-weight: 400;
          margin-top: 2em;
          margin-bottom:2em;
      
      }
        
       img {
        display: block;
        margin: 0 auto;
        max-width: 80%;
        border-radius: 10px;
        padding: 10px 15px;
      }
      button {
        display: block;
        margin: 18px auto;
        background: #556e53; 
        color: white;
        font-size: 12px;
        padding: 10px 15px;
        border: none;
        border-radius: 4px;
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.3);
        transition: all 200ms ease-in-out;
        font-family: Georgia, 'Times New Roman', Times, serif;
        font-size: medium;
        font-weight: 200;} 

        button:hover{
         opacity: 0.9;
        cursor: pointer;
        }
        hr{
    display: block;
    unicode-bidi: isolate;
    margin-block-start: 0.5em;
    margin-block-end: 0.5em;
    margin-inline-start: auto;
    margin-inline-end: auto;
    overflow: hidden;
    border-style: inset;
    border-width: 3px;
        }
        .learn-more{
        display: block;
        margin-top: 10px;
        text-decoration: none;
        color: #556e53; 
        }
        .learn-more:hover{
          text-decoration:underline ;
        }
        .footer {
        text-align: center;
        font-size: small;
        
        }
    .container {
      margin: 25px auto;
      width: 60%;
      padding: 30px;
      background-color: #f5f5f5; 
      border: radius 15px;
      display: block;
}
    </style>
  </head>
  <body>
   <div class="container">
    <h1>INNOCENT BUT DEADLY: A GUIDE ON HOW TO IDENTIFY POISONOUS PLANTS</h1>
    <h2> PLANT: <em>Nerium oleander</em></h2>
    <h3>a.k.a Oleander</h3>
    <p>
     <strong> Summary:</strong> Oleander is an evergreen plant that belongs to the family
      Apocynaceae. This plant is native to Morocco, Portugal, China and
      Mediterranean areas, but it has been naturalized to almost all continents
      in the world. Oleander is one of the most poisonous plants on the planet.
      Despite that fact, people cultivate and create new varieties of oleanders
      due to ornamental morphology of these plants. Oleander grows on the
      well-drained soil in areas that provide enough sunlight. It lives mostly
      in warm, tropical climates, and developes yellow, white, pink, light
      orange, and red flowers. Oleander can tolerate drought and temperatures
      near zero during short periods of time. Besides being popular in
      horticulture, oleander can be used in the pharmaceutical industry for the
      production of various remedies.
    </p>
    <p>
     <strong>Be Aware:</strong>  While the oleander can easily beautify any outdoor space, all
      parts of the oleander plant (leaves, flowers, twigs, and stems), can cause
      sever illness and/or death. Touching the plant can cause skin irritation
      (best to keep these away from pets) and ingesting the plant can cause
      death.
    </p>
    <p>
     <strong> Fun Fact:</strong> Oleander is the official flower of Hiroshima. It was the first plant
      that managed to blossom after devastating effects produced by atomic bomb
      in the 1945.
       <a
          href="https://www.softschools.com/facts/plants/oleander_facts/641/""
          target="_blank"
          class="learn-more"
          >Learn more here
        </a>
    </p>
    <hr> 
     <img
        src="https://s3.amazonaws.com/shecodesio-production/uploads/files/000/014/566/original/201006b-jean-pierre-redoute-.jpg?1628005593"
        alt="Oleander"
        width="300"
      />
      <hr> 
      <button>Does this plant look familiar?</button>
      <p class="footer">
        This page was built by
        <a href="linkedin.com/in/mariam-khan-a1308a16b" target="_blank">
          Mariam Khan
        </a> </p>
      </div>
          <script>
      function ask() {
        let ask = prompt ("Have you seen this plant before?");
       ask = ask.toLowerCase(); if (ask === "yes") {
            alert ("Wonderful! Remember to always wear gardening gloves when admiring nature's beauty 🌿");
    } else {
        alert ("Maybe next time! Remember to always wear gardening gloves when admiring nature's beauty 🌿")
    }
      }
     
      let plantButton = document.querySelector("button");
     plantButton.addEventListener("click", ask);
    </script>
  </body>
</html>
