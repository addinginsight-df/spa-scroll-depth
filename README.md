# spa-scroll-depth
Measure scroll depth in Google Tag Manager, with support for SPA-websites.

Instructions on use:
1. Create a Tag and include the <a href="scroll_depth.html">Custom HTML-code</a>, the triggers for this tag should be both Pageview and History Change (virtual page view).
2. Create a Data Layer Variable and with the variable name "scroll_depth" (if you haven't renamed it in the code).
3. Create a Custom Event trigger and base it on the event "scroll" (if you haven't renamed it in the code).
4. Suggestion: Add a GA4 Event tag, name the event "scroll" and add an Event Parameter, name the parameter "scroll_depth" and put the newly created Data Layer Variable as value.
