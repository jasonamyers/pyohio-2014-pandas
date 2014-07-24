# PyOhio 2014 Introduction to Pandas

## Instructions
1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the repository
   ```sh
   $ git clone https://github.com/jasonamyers/pyohio-2014-pandas.git
   ```

5. Navigate to the repo folder
   ```sh
   $ cd pyohio-2014-pandas.git
   ```

6. Install dependencies
   ```sh
   $ npm install
   ```

7. Serve the presentation and monitor source files for changes
   ```sh
   $ grunt serve
   ```

8. Open <http://localhost:8000> to view your presentation

   You can change the port by using `grunt serve --port 8001`.


### Fullscreen mode
Just press »F« on your keyboard to show your presentation in fullscreen mode. Press the »ESC« key to exit fullscreen mode.

## PDF Export

Presentations can be exported to PDF via a special print stylesheet. This feature requires that you use [Google Chrome](http://google.com/chrome).
Here's an example of an exported presentation that's been uploaded to SlideShare: http://www.slideshare.net/hakimel/revealjs-13872948.

1. Open your presentation with [css/print/pdf.css](https://github.com/hakimel/reveal.js/blob/master/css/print/pdf.css) included on the page. The default index HTML lets you add *print-pdf* anywhere in the query to include the stylesheet, for example: [lab.hakim.se/reveal-js?print-pdf](http://lab.hakim.se/reveal-js?print-pdf).
2. Open the in-browser print dialog (CMD+P).
3. Change the **Destination** setting to **Save as PDF**.
4. Change the **Layout** to **Landscape**.
5. Change the **Margins** to **None**.
6. Click **Save**.

![Chrome Print Settings](https://s3.amazonaws.com/hakim-static/reveal-js/pdf-print-settings.png)



## Speaker Notes

reveal.js comes with a speaker notes plugin which can be used to present per-slide notes in a separate browser window. The notes window also gives you a preview of the next upcoming slide so it may be helpful even if you haven't written any notes. Press the 's' key on your keyboard to open the notes window.

