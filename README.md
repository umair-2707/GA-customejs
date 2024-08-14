create a README.md file that specifies the following information:
- A deatiled description of what the action does.
- required inout and the output arguments.
- optional input and the output arguments.
- secrets the action uese.
- environment variables the action uses.
- an example of how to use your action in a workflow.

# hello world javascripts action 
this action prints "Hello World" or "Hello" + the name of the person to greet to the log.
## Inputs

### 'who-to-greet'

**required** the name of the person to greet. gefault "World".

## Outputs

### 'time'
The time we greeted you .
## Examples usage

```yaml
uses: action/GA-customjs@e76147da8e5c81eqf017dede5645551d4b94427b
with:
  who-to-greet: 'Mona the Octocat'
```
