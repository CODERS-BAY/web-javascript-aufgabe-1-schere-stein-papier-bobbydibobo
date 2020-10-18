for(char of chars){
            char.addEventListener("click", function(e){
                const npcChoiceNumb = Math.floor(Math.random() * 3);
                const npcChoice = npcOptions[npcChoiceNumb];
                let element = e.target || e.srcElement;

                if (element.classList.contains("rock")) {
                    alert("Rock");
                }
                else {
                    if (element.classList.contains("paper")) {
                        alert ("Paper");
                    }
                    else {
                        alert ("Scissors");
                    }
                }