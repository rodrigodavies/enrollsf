enrollsf
========

A Jekyll-based responsive web navigator for health choices.

Instructions (command line)

1. Install Jekyll 
	gem install jekyll

2. Clone this repo into a folder
	git clone https://github.com/rodrigodavies/enrollsf.git

3. From the repo folder, type 
	jekyll serve --watch

4. Go to http://localhost:4000 in your browser

5. To make changes: 
	Changes to css should be made in css/survey-style.css
	Changes to page structure can be made by editing the files in _layouts
	Each view has its own html page, linked to a layout

6. For further instructions on how to use Jekyll, head to jekyllrb.com

7. Each time you run jekyll serve (or update your pages), static html pages are generated in a folder called _site. You can deploy your site by uploading the files in the _site folder directly to your web server -- this may be the easiest option if you are familiar with simple FTP access. Alternatively you can deploy using github pages, and several other methods: http://jekyllrb.com/docs/deployment-methods/