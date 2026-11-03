Y2K Joystick popup visuals (transparent 800x260 HTML browser source).
Open alerts.html?demo=follow in a browser to preview; change follow to sub, tip, large, wheel, wave, etc.
The HTML deliberately does NOT loop or play audio. It is a visual component only.
To trigger from an event, a compatible alert integration must send a browser postMessage with {type:'y2k-alert',event:'follow',username:'Viewer'} to this page.
Joystick's existing sound-bot browser source does not automatically control this separate HTML. Verify whether the bot supports custom visual HTML or events before expecting automatic popups.
