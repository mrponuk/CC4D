# Teams Tutorial

This is a basic tutorial on how to add someone to the Our Team page. To add someone to the teams page you will have to edit the team.json file [found here](https://github.com/mrponuk/CC4D/blob/main/_data/team.json).

## Some Initial Notes

- Every field (html_id, name, role, img and description) **MUST** be included in **EACH** entry.
- Make sure to include a comma after each line and each entry (except the last one).
- I highly recommend testing before you push to live. See [README.md](README.md) to see how to test run the site using docker.

## Example team.json file

    {
        "team": [
            {
                "html_id": "portfolioModal1",
                "name": "Example Name 1",
                "role": "Example Role 1",
                "img": "img/team/example-img1.jpg",
                "description": "Example description text 1"
            },
            {
                "html_id": "portfolioModal2",
                "name": "Example Name 2",
                "role": "Example Role 2",
                "img": "img/team/example-img2.jpg",
                "description": "Example description text 2"
            },
            {
                "html_id": "portfolioModal3",
                "name": "Example Name 3",
                "role": "Example Role 3",
                "img": "img/team/example-img3.jpg",
                "description": "Example description text 3"
            }
        ]
    }

## Breakdown

### html_id

- This must be **UNIQUE** (no duplicates) for every entry.
- For consistency sake, and so nothing is broken by accident please use the format: "portfolioModal**NUMBER**"

### name

- Person's name.

### role

- Person's role in the organisation, ie Founder, Volunteer, etc.

### img

- **All images should have a 10:8 aspect ratio.**
- Place the image file inside [img/team](https://github.com/mrponuk/CC4D/tree/main/img/team).
- Make sure to use the correct file name and extension inside the json file (ie /img/team/FILENAME.EXTENSION)

### description

- This string must be a **single line** due to json formatting, meaning no newlines or line breaks. I recommend typing this up in another program and the copy pasting the string into the json file.
- To create a **newline** (when its rendered on the site) use **\<br>**. Use two of them in a row to start a new paragraph (ie **\<br>\<br>**). This represents a break in html.

As an example, the following:

    "description": "This is the first paragraph.<br><br>This is the second paragraph."

would output to the site:

    This is the first paragraph.

    This is the second paragraph.