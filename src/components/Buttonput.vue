<template>
 <!-- first button option-->
    <html>
        <body>

        <button class="button button1" id="button1" name="ON" v-on:click="pressbutton">On</button>
        <button class="button button2" id="button2" name="OFF" v-on:click="pressbutton">Off</button>
        <button class="button button2" id="button3" name="RESET" v-on:click="pressbutton">Reset</button>
        <button class="button button2" id="button4" name="RESTART" v-on:click="pressbutton">Restart</button>
        <button class="button button2" id="button2" name="ON_1" v-on:click="pressbutton">On 1</button>
        <button class="button button2" id="button2" name="ON_2" v-on:click="pressbutton">On 2</button>
        <button class="button button2" id="button2" name="OFF_1" v-on:click="pressbutton">Off 1</button>
        <button class="button button2" id="button2" name="OFF_2" v-on:click="pressbutton">Off 2</button>
        <button class="button button2" id="button2" name="PULSE_1" v-on:click="pressbutton">Pulse 1</button>
        <button class="button button2" id="button2" name="PULSE_2" v-on:click="pressbutton">Pulse 2</button>
        <button class="button button2" id="button2" name="TEST" v-on:click="pressbutton">Test</button> <br><br>
       
      </body>
    </html>
</template>

<script>
export default {
  methods: {
    pressbutton: function(event) {
      if (event.target.name == "ON")
         {
           alert("Function ten")
          //  alert(event.target.name);
          //  buttonOnePress();
         }
      else if (event.target.name == "OFF")
        {
          alert(event.target.name);
          // buttonTwoPress();
        }
      else if (event.target.name == "RESET")
        {
          alert(event.target.name);
          // resetEEPROM();
        }
      else if (event.target.name == "RESTART")
        {
          alert(event.target.name);
          // rebootEspEveryday();
        }
      else if (event.target.name == "ON_1")
        {
          alert(event.target.name);
          // onRelayOne();
        }
      else if (event.target.name == "ON_2")
        {
          alert(event.target.name);
          // onRelayTwo();
        }
      else if (event.target.name == "OFF_1")
        {
          alert(event.target.name);
          // offRelayOne();
        }
      else if (event.target.name == "OFF_2")
        {
          alert(event.target.name);
          // offRelayTwo();
        }
      else if (event.target.name == "PULSE_1")
        {
          alert(event.target.name);
          // sendPulse(1);
        }
      else if (event.target.name == "PULSE_2")
        {
          alert(event.target.name);
          // sendPulse(2);
        }
      else if (event.target.name == "TEST")
        {
          alert(event.target.name);
          {
            // onRelayOne();
            //  onRelayTwo();
            //  delay(500);
            //  offRelayOne();
            //  offRelayTwo();
            //  delay(500);
            //  sendPulse(1);
            //  sendPulse(2);
          }
        }
      
}//pressbutton method
      

    }//methods
};
</script>

<style scoped>
.button {
  border: rgb(94, 255, 0);
  color: rgb(0, 0, 0);
  padding: 10px 35px;
  text-align: left;
  text-decoration: none;
  /* display: inline-block; */
  font-size: 16px;
  cursor: pointer;
  margin: 10px;

}


</style>
