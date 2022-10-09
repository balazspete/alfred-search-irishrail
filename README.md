# Alfred Irish Rail Realtime API Search
An [Alfred workflow](https://www.alfredapp.com/workflows/) that uses the [Irish Rail realtime API](http://api.irishrail.ie/realtime/) to get the list of available stations and the associated train times within the next 90 minutes.

## How to use the workflow

1. Open the Alfred search UI
2. Type `ir`
    * If you do not provide an argument, the workflow will return the list of all available stations
    <img width="719" alt="image" src="https://user-images.githubusercontent.com/285590/194774951-787cb5d1-7bcd-43fd-a9d3-344dc7dfdefa.png">

    * Provide a substring of the station name to filter the list to the station you're looking for
    <img width="718" alt="image" src="https://user-images.githubusercontent.com/285590/194774982-fc7ff805-1202-406d-9053-7bcc1dc6f2fe.png">
3. Select the station and press enter
4. The workflow will fetch the trains leaving the station within the next 90 minutes
<img width="717" alt="image" src="https://user-images.githubusercontent.com/285590/194775001-9677bbaa-fa52-48d9-a1a9-6da80c6f099a.png">
6. You can quit the workflow here or proceed by pressing enter to set up a notification
7. You can set up a notification/reminder for the train as the thirs step
<img width="717" alt="image" src="https://user-images.githubusercontent.com/285590/194775032-37f8db92-b126-4922-af73-93a793634e92.png">
9. The reminder will be presented in the notification center
<img width="343" alt="image" src="https://user-images.githubusercontent.com/285590/194775150-c7753562-4649-4891-ac11-847737b55569.png">

## Customising notifications

### Delay options
Edit the third (list filter) step which contains the options.
<img width="810" alt="image" src="https://user-images.githubusercontent.com/285590/194775226-c7b8af0d-5ca4-4cfa-8e65-e911c527b92b.png">

The output of this step is passed to the delay operatior. The output needs to be a number representing the number of seconds to wait.

### Sound
You can change the notification sound on the sound step.
<img width="810" alt="image" src="https://user-images.githubusercontent.com/285590/194775290-de731fc9-fc81-4672-b568-d1ee26d0d220.png">

## About
Created the workflow to quickly look up the next train time. Used this to learn more about Alfred workflows.
The workflow scripts are written in Swift.
