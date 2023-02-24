# Chrome-Pdf-dark-mode-

To make the PDF appear darker, kindly copy the code from "Paste this code in your Console.txt" and paste it into your console.



              var cover = document.createElement("div");
              let css = `
                  position: fixed;
                  pointer-events: none;
                  top: 0;
                  left: 0;
                  width: 100vw;
                  height: 100vh;
                  background-color: white;
                  mix-blend-mode: difference;
                  z-index: 1;
                `
              cover.setAttribute("style", css);
              document.body.appendChild(cover);


![image](https://user-images.githubusercontent.com/56159302/221093424-5cb41f42-34f5-46b9-9949-b864407e6954.png)

