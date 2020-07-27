<script src="https://api.glia.com/salemove_integration.js"></script>
<script> 
sm.getApi({version: 'v1'}).then(function(glia) {
  glia.updateInformation({
    "customAttributes":{"chat":"enabled"}
    }).then(function() {
      console.log("Successfully updated visitor attributes");
  }).catch(function(error) {
      console.log("Failed to set attributes for visitor");
  });
});
</script>
  <form action="/">
  <p>Please select your gender:</p>
  <input type="radio" id="male" name="gender" value="male">
  <label for="male">Male</label><br>
  <input type="radio" id="female" name="gender" value="female">
  <label for="female">Female</label><br>
  <input type="radio" id="other" name="gender" value="other">
  <label for="other">Other</label>

  <br>
<div type="numbered" class="ng-scope ng-isolate-scope"><ol ng-transclude="">
<li class="ng-scope ng-isolate-scope"><div ng-transclude="">
Finalize your tax prep
</div></li>
<li class="ng-scope ng-isolate-scope"><div ng-transclude="">
You paid exactly the right amount this year - Nice work!<span class="ta-link-outer ng-scope ng-isolate-scope" type="learn-more" destination="Zero Balance" priv-attrs="{}"><a class="ta-link learnmore indentfix ml-1 " tabindex="-1" onmouseover="window.status='Click to learn more about this topic'; return true;" onmouseout="window.status=''; return true;" href="#" onclick="OnLearnMore('/taxmanager2019/taxmanager.dll/LearnMore?topic=', 'topic:learn more/Zero Balance'); googleAnalyticsEvent('Interview Button', 'Learn More', 'Zero Balance'); return false;"><span ng-transclude=""><i class="icon icon-info"><span class="sr-only">Learn More</span></i></span></a></span>
</div></li>
<li class="ng-scope ng-isolate-scope"><div ng-transclude="">
File your taxes
</div></li>
</ol></div>
   <br> 
   
<style>
.open {
  width: 100%;
  padding: 25px;
  background-color: coral;
  color: white;
  font-size: 25px;
  box-sizing: border-box;
}
</style>

<button onclick="myFunction()">Try it</button>

<div id="gliaDiv" class="element">
This is a DIV element.
</div>

<script>
function myFunction() {
   var element = document.getElementById("gliaDiv");
   element.classList.toggle("open");
}
</script>
  <p>Please select your age:</p>
  <input type="radio" id="age1" name="age" value="30">
  <label for="age1">0 - 30</label><br>
  <input type="radio" id="age2" name="age" value="60">
  <label for="age2">31 - 60</label><br>  
  <input type="radio" id="age3" name="age" value="100">
  <label for="age3">61 - 100</label><br><br>
  <input type="submit" value="Submit">
  <br><br>
  <label for="disabled">Cobrowsing disabled field:</label>
  <input type="text" id="disabled" name="disabled" class="sm_cobrowsing_masked_field"><br><br>
</form>
Back to [tumblr](https://germanprod.tumblr.com/en/english)
To [WebRTC](/webrtc)


<iframe class="EmbeddedAppFrame" src="" cobrowsable_iframe_id="3db11631-642c-4acd-837c-954bc3807afd" cobrowsable_with_mutations="true"></iframe>
<style type="text/css">

    .EmbeddedAppFrame
    {
        height: 960px;
        width: 1020px;
        overflow: hidden;
        background-color: #7c19dd;
        position: relative;
            -ms-zoom: 0.95;
            -moz-transform: scale(0.95);
            -moz-transform-origin: 0px 0;
            -o-transform: scale(0.95);
            -o-transform-origin: 0 0;
            -webkit-transform: scale(0.95);
            -webkit-transform-origin: 0 0
    }

</style>

