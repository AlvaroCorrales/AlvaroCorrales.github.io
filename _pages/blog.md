---
layout: archive
permalink: /_pages/blog/
author_profile: true
title: "Tech blogs"
---

<style>

  @import "compass/css3";

  /* Some vars */
  $background-color: hsl(50, 5, 97);
  $black: hsl(200, 40, 10);
  $white: $background-color;
  $base-font-size: 2.4em;
  $base-line-height: 1.5em;

  .ludwig {
  position: relative;
  padding-left: 1em;
  border-left: 0.2em solid lighten($black, 40%);
  font-family: 'Roboto', serif;
  font-size: $base-font-size;
  line-height: $base-line-height;
  font-weight: 100;
  &:before, &:after {
      content: '\201C';
      font-family: 'Sanchez';
      color: lighten($black, 40%);
   }
   &:after {
      content: '\201D';
   }
  }

.column {
  align-content:center;
  float: left;
  width: 20%;
  height: 100%;
}

.column_home {
  align-content:center;
  float: left;
  width: 20%;
  height: 100%;
}


.center_text {
  align-content:center;
  width: 20%;
  vertical-align: middle;
  text-align:justify;
  text-align-last: center;
}

#left-col {
  align-content:center;
  text-align: center;
  width: 100%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

* {
  box-sizing: border-box;
}

i {
  font-size: 0.4em;
}


#right-col {
  align-content:center;
  text-align: center;
}
</style>

Whether it is for fun or as part of my job, I love writing - although sometimes I don't have as much time as I would like to do it! In this page, you will find some of my latest blog posts about Data Science. Any feedback is welcome!

## Personal publications
<br>
<div id="medium-widget"></div>
<script src="https://medium-widget.pixelpoint.io/widget.js"></script>
<script>MediumWidget.Init({renderTo: '#medium-widget', params: {"resource":"https://medium.com/@acorralescano","postsPerLine":1,"limit":10,"picture":"big","fields":["description","author","claps","publishAt"],"ratio":"landscape"}})</script>
<br>

## IBM-sponsored publications
### Medium
IBM is comitted to sharing knowledge with the broader Data & AI community. As an IBM employee, I have shared my work on Medium publications such as [IBM Data and AI](https://medium.com/ibm-data-ai) and [IBM Garage](https://medium.com/ibm-garage).
<br>
<div id="medium-widget2"></div>
<script src="https://medium-widget.pixelpoint.io/widget.js"></script>
<script>MediumWidget.Init({renderTo: '#medium-widget2', params: {"resource":"https://medium.com/@alvaro.corrales.cano","postsPerLine":1,"limit":10,"picture":"big","fields":["description","author","claps","publishAt"],"ratio":"landscape"}})</script>
<br>

### Other
- [**Causal analysis of the impact of lockdown measures on economic activity**](https://emergentalliance.org/causal-analysis-of-the-impact-of-lockdown-measures-on-economic-activity/) - In this piece of work for the [Emergent Alliance](https://emergentalliance.org/), we show how one can isolate the causal impact of different lockdown measures on social and economic indicators such as energy consumption and people's mobility.  
