### @flyoutOnly true
### @hideIteration true
### @hideIteration true
# QureoMinecraft

## Let's move the agent!

This time we'll use the ``||agent.agent destroy 〇||`` block!

After pressing [](https://raw.githubusercontent.com/qureo-inc/QureoTutorial-prd-en/main/images/playbutton.png) at the bottom right, press the 't' key and enter 'run' to run the program!
```template
player.onChat("run", function () {
    if (hiragana_agent.detect(AgentDetection.Block, FORWARD) == true) {
    }
})
```
```ghost
player.onChat("run", function () {
    if (hiragana_agent.detect(AgentDetection.Block, FORWARD) == true) {
        hiragana_agent.destroy(FORWARD)
    }
})
```