[[2021-10-02_Sat]] created

### scoping
- replacing can be done in place
- only for summaries?
- needs to first find the topmost heading, everything else is then relative to it
- ==super dangerous==, because it may wreck links elsewhere in the vault => must use **LinkNetwork**
- using ensp does not align the numbers correctly, because the numbers in Obsidian have different width => change font ❓
- ⚠️ probably not a good idea to do the numbering in the main vault, better part of publish
- use yaml to turn autonumbering on/off - - gut feeling says default is "off"

<br/>

# example
#### some heading at the start
##### subheading 1
##### subheading 2
### topmost heading
##### subheading 3, skipped
#### subheading 4, correct
##### subheading 5
##### subheading 6

# result
#### 1.1 &ensp; some heading at the start
##### 1.1.1 &ensp; subheading 1
##### 1.1.2 &ensp; subheading 2
### 2 &ensp; topmost heading
##### 2.1.1 &ensp; subheading 3, skipped
#### 2.2 &ensp; subheading 4, correct
##### 2.2.1 &ensp; subheading 5
##### 2.2.2 &ensp; subheading 6

