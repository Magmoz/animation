Animation.css
=========

Bouncy CSS3 animations made simple.

# Installation
'<link rel="stylesheet" href="css/animations.css">'
'<script src="//code.jquery.com/jquery.min.css"></script>'

# Options

## Entrances
.SlideUp
.SlideDown
.SlideLeft
.SlideRight
.SlideExpandUp
.ExpandUp
.FadeIn
.ExpandOpen
.BigEntrance
.Hatch
## Misc
.Bounce
.Pulse
.Floating
.Tossing
.PullUp
.PullDown
.StretchLeft
.StretchRight


Activate an animation on scroll
'<script>
	$(window).scroll(function() {
		$('#animatedElement').each(function(){
		var imagePos = $(this).offset().top;

		var topOfWindow = $(window).scrollTop();
			if (imagePos < topOfWindow+400) {
				$(this).addClass("slideUp");
			}
		});
	});
</script>'

Licensed under the MIT.