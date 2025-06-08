Discussion: Create your own image
--
Try using image primitives to create your own image, and post it to the discussion below. 
Be sure to post both the actual image and the BSL program that produces it. You can look through the  <a href ="https://docs.racket-lang.org/"> HelpDesk </a> to find image primitives you might not be aware of.

-----------------------------------------------
I managed to write a racket code that display the Palestine's Flag.

<br>

Here is my code:

```
(require 2htdp/image)
(above (overlay/align/offset "left" "top"(rotate 217 (triangle/sss 180 150 150 "solid" "red")) 0 0
  (overlay/align/offset "left" "bottom" (rectangle 310 60 "solid" "green") 0 0
  (overlay/align/offset "left" "top" (rectangle 310 60 "solid" "black") 0 0                      
 (rectangle 310 180 "outline" "black") 
)))(text "This is Palestine Flag" 30 "black"))
```

and this is the image displayed 

![image](https://github.com/user-attachments/assets/464e32de-f191-49c7-9d17-058bcbed3884)
