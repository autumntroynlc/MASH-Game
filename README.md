body {
  background: #222629;
  color: #6e6b70;
  font-family: georgia;
  letter-spacing: 2 px;
  font-size: 20px;
  font-weight: 300;
  line-height: 1.65em;
  margin: 0 auto;
  max-width: 800px;
  padding: 40px 10px;  
}

h1 {
  font-size: 80px;
  color: #86C232;
  background:#2f3235;
  font-family: arial;
  text-align: center;
}



.description {
  text-align: center;
  margin: 80px auto 40px;
}


.button-submit {
  background: #2f3235;
  border: 1px dotted #394c58;
  border-radius: 6px;
  color: #86C232;
  cursor: crosshair; 
  display: block;
  font-size: 20px;
  text-transform:lowercase;
  margin: 0 auto 60px;
  padding: 1em 2em; 
  text-align: center; 
  font-family:georgia;
}

.bucket {
  display: inline-block;
  margin-bottom: 40px;
  width: 100%;
}

.choice-bucket {
  display: inline-block;
  float: left;
  margin: 0;
  padding: 0;
  width: 33.333333%;
}

.choice-bucket label {
  font-size: 12px;
  line-height: 13px;
  margin: 15px 4%;
}

.choice-bucket input {
  border: 0;
  border-radius: 6px;
  color: #4c5e5b;
  font-size: 18px;
  margin: 15px 4%;
  outline: 0;
  padding: 16px 0;
  text-indent: 20px;
  width: 92%;  
}

.choice-bucket label ~ input {
  margin-top: 0;
}

.highlight {
  font-size: 18px;
  line-height: 24px;
  margin-left: 30px;
  opacity: .8;
}


#answers {
  margin: 70px 0;
  background: #8e9090;
  border-radius: 2px;
  color: #4c5e5b;
  transition: 1s linear;
}

#answers p {
  max-width: 500px;
  margin: auto;
  padding: 20px 0;
}

#answers p span {
  font-weight: none;
}


.hide {
  opacity: 0;
  height: 0;
}

.show {
  opacity: 1;
  height: 100%;
}
