#flotr2-shade

This Flotr2 plugin shades regions of a [flotr2](https://github.com/HumbleSoftware/Flotr2) graph based on an array of user supplied ranges.

[Example](http://mtmckenna.github.com/flotr2-shade)


Configuration Snippets

// Shade (horizontal shade) from y=0 to y=5
  yaxis : {

               shade: {
                            ranges: [[0, 5]],
                            fillColor: '#344152',
                            fillOpacity: .5
                        } 		              
              
            }

// Shade vertically from x=3 to x=6  and from x=10 to x=15
  xaxis : {

               shade: {
                            ranges: [[3, 6],[10,15],
                            fillColor: '#344152',
                            fillOpacity: .5
                        } 		              
              
            }