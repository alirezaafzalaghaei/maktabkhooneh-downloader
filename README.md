
# maktabkhooneh video downloader
maktabkhooneh.org is virtual digital education school which contains many university courses videos. Unfortunately maktabkhooneh hasn't a good way to download all of videos of an specific course, so i wrote an script which scraps in course page and returns all download links of videos in that course. Note that videos has high-quality.

## Requirements

 - python
 - jupyter-notebook
 - selenium
 - chrome driver (or firefox driver if you change the browser in second cell)

## Usage

- First register an account in maktabkhooneh.org
- Confirm your E-mail
- Clone this repository
- Open notebook file
- Now in 5th cell of notebook write your e-mail and password
- In 6th cell change `course_link` variable to your favorite course
- Finally in kernel menu of notebook hit `Restart & Run All` item.
- Just wait for browser to open, navigate to all courses and then close itself. at the bottom of notebook copy links and download them using your favorite download manager
