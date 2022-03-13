# NLP

<p>Hello everyone. This is a documentation for my YouTube channel where I teach on NLP.</p>
<a href ='https://www.youtube.com/channel/UCMZzuzArMKreKHw-OVbAORA'> Click here for my YouTube tutorials !<a>

<p>I am fairly new and still learning. Let us start with baby steps :)</p>

  <h3>Chapter 1 - Bag of Words</h3>
  <h4>Count Vectoriser</h4>
  <ul>
    <li>a way of representing text data when modeling text with machine learning algorithms.</li>
    <li>A problem with modeling text is that it is messy, and techniques like machine learning algorithms prefer well defined fixed-length inputs and outputs.</li>
    <li>Machine learning algorithms cannot work with raw text directly; the text must be converted into numbers. Specifically, vectors of numbers.</li>
    <li>A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things:
      <ol>
        <li>A vocabulary of known words.</li>
        <li>A measure of the presence of known words.</li>
      </ol>
    </li>
    <li>It is only concerned with whether known words occur in the document, not where in the document.</li>
    <li>The rows indicate the documents in the corpus and the columns indicate the tokens in the dictionary.
</li>
  </ul>
  <h4>TFIDF Vectoriser</h4>
  <ul>
    <li>As compared to Count Vectoriser, it can tells the significance of a given word to a given sentence in a document.</li>
    <li>Can be used to remove stop words.</li>
    <li>Is preffered in most cases, as can lead to more accuracte topic modeling, classification, et cetera.</li>
    <li>DISADVANTAGE: cannot tell the semantics of the word, need to use word embedding for this purpose.</li>
  </ul>
 
  
