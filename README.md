## 1 HTML Issues

> ### Disqus comment section not loading in browser
Browser was open in localhost, and Disqus does not support  `localhost` (file://) for security reasons

**Solution:** Using `Visual Studio Live Server` to make the domain such as 127.0.0.1:"port #"

>### URL in GA and the actual website visited are different. How is the traffic tracked down still?
Put Github link in the GA container when setting up, but the link for the targeted website is compeletely different than what is in GA. How is it possible?

**Solution:** The link in the container is only for ref. What GA sees for traffic tracking is the `code` given to be pasted into the source of the website. It has unique ID # something like `G-XXXXX`

>### Wanna pull a list of contexts close to the title right above by using margin tag
Used margin tag by wrapping around the list using p tag, then added style margin-top tag to shorten the distance in-between. But no changes made.

**Solution:** Instead of wrapping the list tag with p tag, add style tag right into the h tag (h1 style="margin-bottom: "n px;"). It is against HTML rule to contain list tag in the p tag since p tag is a tag that indicates paragraph. They are two seperate entities.
