@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'poppins', sans-serif;
}

body {
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 5px;
  background-image: url("img/fundo\ 2.png");
}

body h2 {
  color: white;
}

main {
  background-color: white;
  padding: 10px;
  border-radius: 10px;
  width: 100%;
  max-width: 700px;
  min-height: 200px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.content {
  display: flex;
  flex-direction: column;
  width: 100%;
  gap: 10px;
}

.spnQtd {
  text-align: end;
}

.answers {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

button{
  width: 100%;
  text-align: start;
  padding: 5px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  background-color: #008CCC;
  color: white;
}

.finish {
  display: none;
  flex-direction: column;
  gap: 10px;
}

.finish button {
  text-align: center;
}

.botao{
  position: fixed;
  bottom: 10px;
  left: 10px;
  padding: 8px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  color: black;
}
