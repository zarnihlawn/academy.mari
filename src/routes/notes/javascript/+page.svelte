<script>
//   const cars = {type:"Fiat", model:"500", color:"white"};  
//   const myArray = Object.values(cars);
//   let myString = JSON.stringify(cars);
//   const exampleString = `dihwad
//   djpw
//   adiwhi
//   aiodhw`
//   const example = "aidwaidbaiufebiab"


//   for (let car in cars) {
//     console.log(cars[car])
//   };


//   console.log()

//   console.log(myString)

//   console.log(exampleString)


//   let text = "5";
//   let padded = text.padStart(4," ");
//   console.log(padded)



// let price = 10;
// let VAT = 0.25;

// let total = `Total: ${(price * (1 + VAT)).toFixed(2)}`;

// console.log(total)

// let array = [10, 39, 318, 489]

// console.log(array.pop())

// array.push(8000)

// array.shift()
// array.unshift(200)

// console.log(array)

</script>

<div class="main">
  <div class="header">
    <div class="title">
      JavaScript Course
    </div>
  </div>
  <div class="body">
    <section>
      <h1>Variable</h1>
        <h2>The use of variables</h2>

              <dl>
                <dt>"const" variables</dt>
                <dd>"const" variables can be used when you don't and can't change the value</dd>
                <dd>
                  <em>Examples<em><br>
                    const number = 0; <br>
                    number = 3(this cannot be changed)
                </dd>
            </dl>

            <dl>
                <dt>"let" variables</dt>
                <dd>"let" variable can be used when you want to change the value whenever needed</dd>
                <dd>
                  <em>Examples<em><br>
                    let number = 0; <br>
                    number = 3(the value has changed);
                </dd>
            </dl>
 
    </section>
        
    <section>
      <h1>Data Types</h1>
          <p>Types are kinds of values that you can work with using variables.</p>

          <p><em>Types can be defined as following<em></p>
            <dl>
              <dt>"Number" Data Types</dt>
              <dd>Number: for all numbers, whether they're integers or decimals</dd>
              <dd>
                <em>Example</em> <br>
                let age = 18;
              </dd>
            </dl>

            <dl>
              <dt>"String" Data Types</dt>
              <dd>String: for all texts, they are written between two quotes ""</dd>
              <dd>
                <em>Example</em>
                let name = "Steve"; <br>
                let sentence = "Hello, world";
                <p>We can even use empty string to redefine the value. 
                  <br>
                  For example; <br>
                  let name = '';

                </p>

              </dd>
           
            </dl>

            <dl>
              <dt>"Boolean" Data Types</dt>
              <dd>Boolean: for the values of true or false, they can be used in condition statement</dd>
              <dd>
                <em>Example</em> <br>
                let isStudent = false;
              </dd>
            </dl>

             
            <dl>
              <dt>"Null" Data Types</dt>
              <dd> for the value of "nothing" or "no value"</dd>
              <dd> 
                <em>Example</em> <br>
               let emptyValue = null;
              </dd>
            </dl>

            <dl>
              <dt>"Object" Data Types</dt>
              <dd> An object is a collection of key-value pairs, that can be used to store related data and sometimes function. </dd>
              <dd>
                <em>Example</em>
                <div>
                let greeting = &#123; <br>
                  user: name; <br>
                  age: 20; <br>
                  isStudent: true; <br>
                  greeting: function() &#123; <br>
                    console.log("I am Steve") <br>
                  &#125;
                &#125;
                </div>
              </dd>
            </dl>

            <dl>
              <dt>"Array" Data Types</dt>
              <dd> An array is a list of that stores multiple values in one variable.
                  <br>
                <em>Example</em> <br>
                  let name = ["Steve", "Eric", "Alex"];
                <p>These can be used as following:  </p>
                  console.log(name[0]);
                </dd>

            </dl>
            
    </section>
    
    <section>
      <h1>Comments</h1>
        <p> A comment is a note in code that JavaScript ignores. They are used to explain the codes written below as a title or to temporarily disable parts. <br>
          <br>
          There are two types of comments.</p>
        <ol>
          <li>Single-line Comment:</li>
              <p>
                We use // at the beginning of the line to comment out a single line.  <br>
                // This is a single-line comment
              </p>
          <li>Multi-line Comment:</li>
              <p>
                We use /* */  to comment out multiple lines. <br>
                /* 
                  This is the first sentence. <br>
                  This is second sentence.
                */
              </p>
        </ol>
            <p>Comments help make code clearer and easier to read.</p>

    </section>
    
    <section>
      <h1>Condition</h1>
        <p>Condition is a statement to run the codes only when something is true. And if not, run the other one.</p>

        <p>We will use two conditional types: If statement and switch statement.</p>
          
        <dl>
          <dt>1.&nbsp;We use If-condition with if, else if and else.</dt>
            <dd>
              let score = 60;
                <br>
              if (score === 100) &#123 <br>
                    console.log("A+! You are special one!"); <br> 
                &#125; <br>

                  else if (score &gt;= 80) &#123; <br>
                      console.log("You pass the test with A"); <br>
                  &#125; <br>

                  else if (score &lt; 40) &#123; <br>
                      console.log("Oh, you failed the test. Try harder next time. will you?"); <br>
                  &#125; <br>
                  
                  else &#123; <br>
                        console.log("You pass the test."); <br>
                        &#125;
            </dd>
        </dl>

        <dl>
          <dt>2.&nbsp;We use switch condition as an alternative to if-condition when we have a lot of options to  handle. <br>
            We use switch, case, default and break.
          </dt>
          <dd>
            let score = B; <br>

            switch(score) &#123; <br>
              &nbsp; &nbsp; case 'A+': <br>
            console.log("A+! You are special one!"); <br>
              &nbsp; &nbsp; break; <br>
              
              &nbsp; &nbsp; case 'A': <br>
              console.log("Wow, you pass the test with flying colors."); <br>
              &nbsp; &nbsp; break; <br>

              &nbsp; &nbsp; case 'B': <br>
              console.log("You pass the test."); <br>
              &nbsp; &nbsp; break; <br>

              &nbsp; &nbsp; case 'C': <br>
              console.log("You pass the test but need a little more effort."); <br>
              &nbsp; &nbsp; break; <br>

              &nbsp; &nbsp; case 'D': <br>
              console.log("Oh, you failed the test. Try harder next time. will you?"); <br>
              &nbsp; &nbsp; break; <br>

              &nbsp; &nbsp; default: <br>
              console.log("You haven't received the score yet."); <br>

          </dd>
        </dl>

    </section>

    <section>
      <h1>Loop</h1>
        <p>Loop is used</p>
    </section>
  </div>
</div>