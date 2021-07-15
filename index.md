<html>
    <head>
        <title>Title of Paper</title>
        <meta charset="utf-8">
        <link rel="stylesheet" href="style.css">
        <script src="index.js"></script>
    </head>
    <body>
        <div class = "center">
            <h1>Finding geographical locations in Marianne Moore's poems</h1>
            <h2>Pradyun and Aadhavan</h2>
            <p>We used a named entity recognition (NER) model. This finds words or phrases that fall under specific categories. The categories that we care about are the ones that correspond to a location. Though the model finds entities that don't fall under these categories, we only print out those that do. These include GPE (geopolitical entity - countries, cities, states, etc), LOC (non-GPE location - mountain ranges, bodies of water, etc), and NORP (nationality, religion, political organization). The model seems to find a lot of locations, but it also classifies some things that aren't locations as locations (ex. misfortune).</p>
            <h3>Our resources</h3>
            <a href="https://spacy.io/usage/linguistic-features#named-entities">Spacy Named Entity Recognition</a><br>
            <a href="https://medium.com/spatial-data-science/how-to-extract-locations-from-text-with-natural-language-processing-9b77035b3ea4">Helpful Article</a>
            <h3>View Our Code!</h3>
            <script src="https://gist.github.com/pradyunSolai/96abb0bbc0a1ae0e477725a88765e062.js"></script>
        </div>
    </body> 
</html>
