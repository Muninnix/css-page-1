# css-page-1
/* * Balise body*/
body {
  background-color: #8ec0e4;
  padding: 0;
  margin: 0;
}
/* * Menu Header*/
header {
  background-color: #d4dfe6;
  border-color: #6aafe6;
  padding: 1% 4px;
  border-width: 1px 0px 3px 0px;
  border-style: solid dotted;
  display: flex;
  align-items: center;
}
.btnMenuLeft {
  
  display: flex;
  /* align-items: center; */
  flex: 90 900px;

}
.btnAnnonce {
  background-color: #6aafe6;
  color: #d4dfe6;
  text-align: center;
  font-size: 20px;
  width: 40%;
  border-radius: 10px;
}

.btnRecherche{
  background-color: #6aafe6;
  color: #d4dfe6;
  text-align: center;
  font-size: 20px;
  width:30%;
  border-radius: 10px;
}

.btnMenuCenter {
  display: flex;
  align-items: center;
  flex: 1 1 400px;
}
.btnMenuRight {
  display: flex;
  justify-content: space-between;
}
.itemMenu {
  margin: 1%;
  font-size: 1;
}
.textMenu{
  font-family: 'Days', sans-serif;                                        
  width: 50%;
  font-size: 28px;
  color: #6aafe6;
}
.fas {
  font-size: 5ex;
  color: #6aafe6;
  margin-left: 15px;
  margin-right: 15px;
}
.fa-address-book {
  margin-right: 78px;
}

/* *Section Annonce*/
.annonceMenuList {
  background-color: #d4dfe6;
  padding: 5%;
  padding-bottom: 2%;
  margin: 5%;
  border-radius: 50px;
  display: flex;
  align-items: center;
  flex-direction: column;
}
.container {
  color: #6aafe6;
  font-size: 18px;
  font-weight: bolder;
  display: flex;
  flex-wrap: wrap;
  row-gap: 1em;
  column-gap: 40px;
  margin: 3%;
  padding: 1%;
  width: 80%;
  height: 200px;
  border: 1px solid #c3c3c3;
  border-radius: 20px;
  box-shadow: 8px 8px 10px 0 rgb(0 126 73 / 50%);
}
.item1 {
  width: auto;
  padding: 10px;
  flex: 1 1 300px;
}


/*! Card Saving html*/
.cardNameBalise{
  margin: 2%;
}
.dateCrypto{
  display: flex;
      margin: 1%;
}

.dateCrypto p {
  margin: 1%;
}
