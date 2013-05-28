Heroku buildpack: ImpactStory
========================

This is a buildpack to install Python and Perl dependencies in order to run the ImpactStory CV parser.
This custom buildpack is essentially a mashup of the Python and Perl buildpacks. All of the logic for
setting up ParsCit on Heroku is in /bin/compile.
