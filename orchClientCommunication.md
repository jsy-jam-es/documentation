# orchClientCommunication

## client

### setName
````
{
    type: "setName",
    name: "berthold"
}
````

### vote
````
{
    type: "vote",
    pollId: 1337,
    optionId: 1
}
````


## orchestrator

### scene
````
{
    type: "scene",
    sceneId: 122,
    description: "you wake up in a phone booth, stark naked",
    options: [
        {
            id: 1, 
            title: "you run away screaming"
        }, 
        {
            id: 2,
            title: "you think about all the decisions you took in your life
        }
    ]
}
````