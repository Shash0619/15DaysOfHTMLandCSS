/* Universal Selector */
{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Element Selector */
h1 {
  color: navy;
}

/* ID Selector */
#main-heading {
  font-size: 2rem;
}

/* Class Selector */
.highlight {
  background-color: yellow;
  padding: 10px;
}

/* Descendant Selector */
div p {
  font-style: italic;
}

/* Child Combinator */
ul > li {
  list-style-type: square;
  margin-left: 20px;
}

/* Adjacent Sibling */
h2 + p {
  color: gray;
}

/* General Sibling */
h2 ~ p {
  color: teal;
}
