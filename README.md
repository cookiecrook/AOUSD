# Alliance for Open USD, Accessibility Use Cases

Placeholder repository to move accessibility use cases into code samples with visual explanations.


### Updating a label for a blind user.
If needed, accessibility information can be updated across time, such as this 
example of a crosswalk sign changing from _Walk_ to _Don't Walk_.

```{code-block} usda
string accessibility:default:label.timeSamples = {0: "Walk", 10: "Don't Walk"}
```
- Pull Request: [Include time-variable example in Accessibility API docs - OpenUSD #4008](https://github.com/PixarAnimationStudios/OpenUSD/pull/4008)
