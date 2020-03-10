On desktop the images could represent their full content while adjusting size and maintaining ratio.
However, for the mobile view, it's desired that the image be set as a thumbnail box. These two diferences meant
using the same image source while changing the portion of the image that was displayed. To solve this issue,
the image was set in a div as a background image instead of as an image element. Sizing issues arised with the div sizing dynamically on desktop to accomodate
the flexible grid while also maintaining aspect ratio. The solution was to use padding and %s to maintain ratio, since the image width and height were a 2 to 2 relationship.

When switching to mobile, background position needed to be added to keep the image centered.

Biggest lesson learned: padding percentages are measured by the width of the container the element is in. Not the height!
