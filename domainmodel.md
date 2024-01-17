| Classes | Variables    | Methods                | Scenario       | Output |
|---------|--------------|------------------------|----------------|--------|
| Car     | String color | setColor(String color) | Set color      | true   |
|         |              |                        | Cant set color | false  |
I want to be able to decide on the colour of the car.

I want to be able to choose between rechargable and disposable batteries.

| Classes | Variables           | Methods  | Scenario                  | Output |
|---------|---------------------|----------|---------------------------|--------|
| Car     | Boolean rechargeble | choose() | Rechargeble or disposable | true   |
|         | Boolean disposable  |          | Non                       | false  |

I want to choose between a simple and an advanced remote control.

| Classes | Variables        | Methods          | Scenario           | Output |
|---------|------------------|------------------|--------------------|--------|
| Car     | Boolean simple   | simpleAdvanced() | Simple or advanced | true   |
|         | Boolean advanced |                  | Non                | false  |

I want to be able to see the battery percentage remaining.


| Classes | Variables              | Methods   | Scenario     | Output |
|---------|------------------------|-----------|--------------|--------|
| Car     | Integer battery status | battery() | Battery left | true   |
|         |                        |           | Non          | false  |

I want to be able to move the car forward and backward a specific distance.


| Classes | Variables        | Methods | Scenario  | Output |
|---------|------------------|---------|-----------|--------|
| Car     | Integer forward  | move()  | Can move  | true   |
|         | Integer backward |         | Cant move | false  |

I want to be able to stop the car from moving.


| Classes | Variables         | Methods | Scenario    | Output |
|---------|-------------------|---------|-------------|--------|
| Car     | Boolean isStopped | stop()  | Stopped     | true   |
|         |                   |         | Not stopped | false  |

I want to be able to turn the car left and right.


| Classes | Variables        | Methods | Scenario      | Output |
|---------|------------------|---------|---------------|--------|
| Car     | Boolean simple   | turn()  | Left or right | true   |
|         | Boolean advanced |         | Not turning   | false  |

I want to be able to replace the battery with either kind as needed.


| Classes | Variables        | Methods   | Scenario     | Output |
|---------|------------------|-----------|--------------|--------|
| Car     | Boolean replaced | replace() | Replaced     | true   |
|         |                  |           | Not replaced | false  |