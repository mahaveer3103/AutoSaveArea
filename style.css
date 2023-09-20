const text=document.getElementById("text");
const dark=document.getElementById("dark");
const light=document.getElementById("white");


text.addEventListener("input", saveInLocalArea);

function saveInLocalArea(){
    localStorage.setItem("saved", text.value);
}

if(localStorage.getItem("saved")){
    text.value=localStorage.getItem("saved");
}

dark.addEventListener("click", () => {
    document.body.style.backgroundColor = "black";
})

light.addEventListener("click", () => {
    document.body.style.backgroundColor = "white";
})
