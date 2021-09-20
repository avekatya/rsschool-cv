# CV

***Name and surname:*** _Katsiaryna Averchanka_    
***Contact info:***    
_email: katyaaverchenko@gmail.com_    
_mobile phone: +375291121296_ 

***A bit about myself***  
My goal is to learn JS well enough to start working as a Front-end developer by the beginning of autumn.    
I used to work as a Sales Manager which means:
> - I know how to __sell myself__ (I mean I know how to **do well** in an interview);
> - my **English level is high**;
> - I've got great **soft skills** (plus I _listen to people_ and I _hear them_);
> - I'm not afraid of **advancing my ideas**;
> - I'm able to **handle stress** (nothing is more stressful than sales, _imho_).

***Technologies and frameworks***   
Technologies that I use include **HTML, CSS, JavaScript**.

***My code example***   

```
let operationButtons = document.getElementsByClassName('operation-button');


const input1 = document.getElementById('input1');
const input2 = document.getElementById('input2');


function makeOperation(operationCode) {
    const number1 = Number(input1.value);
    const number2 = Number(input2.value);
    let result;
    if (operationCode === '+') {
        result = number1 + number2;
    }
    else if (operationCode === '-') {
        result = number1 - number2;
    }
    else if (operationCode === '*') {
        result = number1 * number2;
    }
    else if (operationCode === '/'){
        result = number1 / number2;
    }
    else {
        window.alert("operation is unknown");
    }

   window.alert(result);
}

function onOperationButtonClick (eventObject) {
    let clickedElement = eventObject.currentTarget;
    let operation = clickedElement.innerHTML;
    makeOperation(operation);
}

for (let operationButton of operationButtons) {
        operationButton.addEventListener('click', onOperationButtonClick); 
    } 
 ```
***Working experience***  
_I haven't got relevant working experience by now. This section will be updated soon though._

***Education*** 
- Bachelor's degree in Intercultural Communication (MSLU);
- IT Kamasutra video course on JS;
- HTML Academy web development course.

***English level***    
C1+
