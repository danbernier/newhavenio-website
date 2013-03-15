NHV.io
======

This is the code for the [nhv.io](http://www.nhv.io) website.  Just a placeholder right now.
If you'd like to help build something, please get in touch: I'm @4242jensen on Twitter.

## Requirements

The placeholder site is statically generated assets that are hosted on AWS's S3.

To deploy the site you'll need [s3cmd](http://s3tools.org/s3cmd), which you can install
as a Ruby gem or via homebrew, e.g.

	brew install s3cmd

You'll also need a `.s3cfg` file containing at least the following lines

	[default]
	access_key=YOUR-ACCESS-KEY-GOES-HERE-YO
	secret_key=YOUR-SECRET-KEY-GOES-HERE-YO

You can get deployment keys from Kyle.