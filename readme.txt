=== ChordChartWP ===
Contributors: faniry
Donate link: https://www.paypal.me/rafaniry
Tags: chord chart, tablature, chordpro
Requires at least: 4.6
Tested up to: 4.7
Stable tag: 4.3
Requires PHP: 5.2.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Users write shortcodes of text tab notation which will be then be parsed and rendered as svg chord chart images. 

== Description ==

This is a wordpress shortcode for the javascript library chordography2 (https://chordography2.blogspot.com/). 
It is easy to use, plug and play, and can be intensively costumized with several parameters. 

The database of chords are designed for guitar and are only the major non-chromatic chord "A,B,C,D,E,F,G". This
will grow and will be updated in the future. 

To visualize a chord from the database write

	[chordChart title="C"]

For more chords from the database

	[chordChart title="A,B,C,D,E,F,G"]

For custom chords

	[chordChart title="Am7,DM7" frets="x02010,x57675" labels="xx2x1x,x13241"]
	
For mixed of chords from database and custom chords

	[chordChart title="C,D,Em" frets=",,022000" labels=",,x12xxx"]

For chord in higher position of the neck you could use parantheses to define them

	[chordChart title="C" frets="8(10)(10)988" labels="134211"]

User could also ignore the label parameter but then the barre sign will not be rendered for E-shape and A-shape chords.

To change the style, you could use parameter such as style="pretty" or cellHeight=34, etc.,. in the short code. The other parameter can be found in the chart.data.js file

== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files 'ChordChartWP' to the `/wp-content/plugins/` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress


== Frequently Asked Questions ==

= I cannot see the rendered chord image?=

Please update your browser or check the developer console for possible errors.

== Upgrade Notice ==
Install over previous version.

== Screenshots ==

1. Examples of rendered svg guitar frets using ChordChartWP

== Changelog ==

= 1.0 =
* Initial creation. Used privately on https://gasytablature.com

