# Main Title

![My Image](https://github.com/shamim-akhtar/gdd-sample/blob/main/MicrosoftTeams-image.png)

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

## This is a video


https://user-images.githubusercontent.com/7691849/135415877-9bfc7e47-b308-4073-81c3-c728c8fcb015.mp4



[Read the tutorial before coming to class](https://github.com/shamim-akhtar/tutorial-pathfinding)

**This is a bold text**

## Heading 2
> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam volutpat egestas nibh at ultricies. Aenean vestibulum quam sed leo elementum, pellentesque fermentum arcu vulputate. Curabitur dictum varius lacus, vel fringilla est accumsan vitae. Sed ac nunc sem. Pellentesque tristique odio non purus aliquam, at dapibus nisl accumsan. Duis eleifend elementum tristique. Quisque nulla metus, faucibus et mauris ac, pharetra ullamcorper magna. Donec tincidunt ac ligula id pulvinar. In tempus volutpat eros at accumsan.

### Heading 3

**Code Sample**

``` csharp
  public class State<T>
  {
    // The name for the state.
    public string Name { get; set; }

    // The ID of the state.
    public T ID { get; private set; }

    public State(T id)
    {
      ID = id;
    }
    public State(T id, string name) : this(id)
    {
      Name = name;
    }
  }
      
```

### This is a list
- Item 1
- Item 2
  - Item 2.1


### This is a table
#### A Table
<table>
 <tr>
  <td>Current State</td>
  <td>Input</td>
  <td>Next State</td>
  <td>Output</td>
 </tr>
 <tr>
  <td rowspan="2">Locked</td>
  <td>coin</td>
  <td>Unlocked</td>
  <td>Unlocks the turnstile so that the customer can push through.</td>
 </tr>
 <tr>
  <td>push</td>
  <td>Locked</td>
  <td>None</td>
 </tr>
 <tr>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
 </tr>
 <tr>
  <td rowspan="2">&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
 </tr>
 <tr>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
  <td>&nbsp;</td>
 </tr>
</table>
