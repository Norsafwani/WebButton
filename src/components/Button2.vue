<template>
    <!-- Second button option -->
<div>
        <button class="button" id="button1" name="ON" v-on:click="buttonOnePress">On</button>
        <button class="button" id="button2" name="OFF" v-on:click="buttonTwoPress">Off</button>
        <button class="button" id="button3" name="RESET" v-on:click="resetEEPROM">Reset</button>
        <button class="button" id="button4" name="RESTART" v-on:click="rebootEspEveryday">Restart</button>
        <button class="button" id="button5" name="ON_1" v-on:click="onRelayOne">On 1</button>
        <button class="button" id="button6" name="ON_2" v-on:click="onRelayTwo">On 2</button>
        <button class="button" id="button7" name="OFF_1" v-on:click=" offRelayOne">Off 1</button>
        <button class="button" id="button8" name="OFF_2" v-on:click="offRelayTwo">Off 2</button>
        <button class="button" id="button9" name="PULSE_1" v-on:click="sendPulseOne">Pulse 1</button>
        <button class="button" id="button10" name="PULSE_2" v-on:click="sendPulseTwo">Pulse 2</button>
        <button class="button" id="button11" name="TEST" v-on:click="test">Test</button> <br><br>
       
</div>


</template>

<script>
export default {
    name:'Button2', 

    methods:
    {
       buttonOnePress()
        {
            // Function Button here
            alert("buttonOnePress();")
        },

       buttonTwoPress()
        {
             // Function Button here
            alert("buttonTwoPress()")
        },
       resetEEPROM()
        {
             // Function Button here
            alert("resetEEPROM();")
        },
       rebootEspEveryday()
        {
             // Function Button here
            alert("rebootEspEveryday();")
        },
       onRelayOne()
        {
             // Function Button here
            alert("onRelayOne();")
        },
       onRelayTwo()
        {
             // Function Button here
            alert("onRelayTwo();")
        },
       offRelayOne()
        {
             // Function Button here
            alert("offRelayOne();")
        },
        offRelayTwo()
        {
             // Function Button here
            alert("offRelayTwo();")
        },
       sendPulseOne()
        {
             // Function Button here
            alert("buttonOnePress();")
        },
       sendPulse()
        {
             // Function Button here
            alert("buttonOnePress();")
        },
       test()
        {
             // Function Button here
            alert("test();")
        }


    }
}
</script>

<style scoped>
.button {
  /* border: rgb(94, 255, 0); */
  color: rgb(102, 69, 17);
  padding: 10px 35px;
  text-align: left;
  text-decoration: none;
  /* display: inline-block; */
  font-size: 16px;
  cursor: pointer;
  margin: 10px;
  border-radius: 8px;
  background-color: white;
  color: black;
  border: 2px solid #ffd207; /* Green */}

.button:hover {
  background-color: #c0ae0a;
  color: white;
}





</style>