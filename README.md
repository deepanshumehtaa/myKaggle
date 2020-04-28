# Prevent the Google colab to disconnect??

change the java script code, by clicking the inspect element > console
and paste the JS code given below:

    function ClickConnect(){
    console.log("Working"); 
    document.querySelector("colab-toolbar-button#connect").click() 
    }
    setInterval(ClickConnect,60000)
