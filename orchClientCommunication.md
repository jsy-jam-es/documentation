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
````
{
    type: "poll",
    pollId: 122,
    options: [
        {
            id: 1, 
            title: "you run away screaming"
        }
    ]
}
````