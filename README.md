# Result gallery

The result gallery project aims at fostering data and result dissemination in a research consortium. It takes for granted that the unit of information exchange is the scientific figure, and try to build a nice-looking and engaging way to share these figures with colleagues.

# The .dar format for SmartFigures

Scientific figures comprise not only the figure, but also metadata about the experiment (link to the data, protocol, material used,...), experimenter, and description (caption). The whole is packed in a specific xml format (jatsxml) publishers are using/developing in the texture project. In reality, it is a .zip archive containing specific xml files and the image, while other elements can be added.

Since it is a unique file, it is easy to share and transfer, we call it the SmartFigure.

# the prototype

We used Rshiny to build a prototype to gather early feedback and work on the design. The prototype do not use xml (yet?) and provide a google-image-like visualisation (using blogdown, hugo and specific css and js commands).
The SmartFigures themselves are saved on a dropbox folder, so no previous installation is needed. Dropbox and third party software are used to send news (on slack) and write comments on the figure.

# the sourcedata dashboard

The final software will be an open source software to be installed on one's own server. It will be more complexe and allow for more automation and features and scalability.
