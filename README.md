UIMarqueeLabel
==============

Marquee Label for iOS , easy Implement in UIBuilder

Class
  - UIMarqueeLabel.h
  - UIMarqueelabel.m
  (Need add CoreGraphics.framework )
  

How to use
  - by Builder
    1.Drag UILabel to View
    2.Add your text and resize Label frame to whatever you want
    3.add custom class to UIMarqueeLabel
    4.if text lenght is more than frame it will automaticlly move from right to left
  - by programmatically
    1.Import UIMarqueeLabel.h
    2.init Object UIMarqueeLabel with frame
    3. set up your text style
    
Property
  - (int)velocity : how fast of text animation (default 25)
  - (int)delay : delay time before text start animation (sec)
  - (UIColor)themeTextColor : text Color
  - (UIFont)LabelFont : text font
  - (float)LoopSpace : space of gap between end and start of text when text carousel
 
Method
  - setText:Text withAnimate:animate
      setUIMarquee content Text (will animate if text lenght is over the frame and animate YES)
  -startAnimate
      start text animation
  -stopAnimate
      stop text animation
    
  
