# Simple-Javascript-Personality-Quiz

This is an experimental pure javascript quiz application which does not require any programming knowledge outside of basic HTML to use. The script was created in 2015 with the intention of allowing indviduals with no experience of programming outside of HTML to create an online quiz without having to deal with an interface to create one.

### How it works

The quiz questions and  answers are defined in HTML using the set of tags and onclick methods defined below. 


#### Defining Questions
The div block which tonains the answers to the question. The ID should start off as the number one and increment for each question. 
```html 
<div class="question invisible" id="question-1">
 yada yada yada
</div>
```

#### Defining Answers
Create a custom attribute called data-endingsentence and define what text should be added at the quiz summary. You should add a name attribute called "rq" and assign an onclick method to setAnswerButton().

```html
<input data-endingsentence="As a young child you grew up in Redania (located in the Northern Kingdoms) enjoying prosperity the nation held." name="rq" onclick="setAnswerButton()" type="radio">Redania
 ```
 
 #### Defining Quiz Results
Simply include the following block and the answers will be aggregated together and placed within the generated_text div. 

```html
<div class="invisible" id="results_screen">
  <h2 class="section-heading text-center">Who are you?</h2>
  <div id="generated_text">
	 </div>
</div>
 ```
### License
[See license file](/LICENSE.md)
