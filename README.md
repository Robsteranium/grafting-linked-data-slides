# Grafting Linked Data (what a billion rows taught us about pipelines)

A presentation prepared for Clojure Berlin: http://www.meetup.com/Clojure-Berlin/events/226728445/.

This talk is based upon our experiences creating [Grafter](http://grafter.org), a library for turning spreadsheets into linked-data produced by [Swirrl](http://swirrl.com) for their PublishMyData platform.

For those new to clojure we introduce the threading macro and show how it can be used to create more legible data processing pipelines.

For those more familiar with clojure we share some tips for the efficient processing of lazy sequences (in particular, how to avoid holding onto the head of the sequence).

A general introduction to linked-data and RDF is provided, no background knowledge is required.


## Building the slides

You'll need `npm` to build these slides. First get the dependencies:

    npm install

To have the slides regenerated as you edit [index.haml](/index.haml):

    npm run watch

Or to build the slides one time:

    npm run prepare

Or to create a zip of the content for deployment:

    npm run archive

## License

These slides are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International Public License](https://creativecommons.org/licenses/by-sa/4.0/).

They were built using [Shower](https://github.com/shower/shower) which is released under an MIT License. 