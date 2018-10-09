@title[Marquee Code Preview]
# Marquee Code Preview

---?code=src/Marquee/MarqueeDecorator.js&lang=javascript

@[271-285](Constructor)
@[294-301](componentWillMount showing connection to MarqueeController)
@[723-732](RTL determination)
@[119-124](Decorator timer states)
@[516-538](Start method)
@[517-520](Bail out early if marquee is disabled)
@[521](If we're already animating, :nothingtodohere:)
@[526-536](Start a timer, based on the passed delay)
@[528-532](If, after measuring, we need to start, update state)
@[533-535](If we didn't need to marquee and we're sync, alert the controller we're done)

---?code=src/Marquee/MarqueeController.js&lang=javascript

@[19-78](MarqueeController context object)
@[53-59](register method, accepts the start and stop methods of MarqueeDecorator)
@[7-11](Controller states)
@[197-204](Handling a start request)