# YouTube UI Clone Assignment CSS

## Hosted Link: [View Live Project](https://saifulislam05.github.io/youtube-clone/)
## Project Description
The "YouTube UI Clone" project is a web page that replicates the design of the YouTube video streaming platform's user interface. It includes a header section, a side-bar navigation menu, and a video content section.

## HTML Explanation

### Header (`.header`)
![image](https://github.com/saifulislam05/youtube-clone/assets/73392705/7d57ef8d-90bf-48c8-9499-7c659683c527)

- The header section contains the logo, search bar, and navigation icons.
- The logo is a combination of an icon and an image.
- The search bar allows users to input search queries.
- Navigation icons include icons for videos, grid, notifications, and user profile.

### Side-bar (`.side-bar`)
![image](https://github.com/saifulislam05/youtube-clone/assets/73392705/b5c7a6df-78f4-45e6-ad4a-d9d615bcfd7e)

- The side-bar is a navigation menu that includes links to various sections of the YouTube app.
- It is divided into two sections: "Main" and "Library."

### Videos Section (`.videos`)
![image](https://github.com/saifulislam05/youtube-clone/assets/73392705/c5dbfc8b-81dd-4034-b16b-4bbd94785281)

- The videos section displays a list of video thumbnails, titles, authors, and view counts.
- It includes a "Recommend" heading.

## CSS Explanation

### Global Styles (`*`)
- `margin: 0;` sets the margin to zero for all elements.
- `padding: 0;` sets the padding to zero for all elements.
- `box-sizing: border-box;` includes padding and border in element width and height calculations.

### Header Section (`.header`)
- Styles the header section at the top of the page.
- It includes the logo, search bar, and navigation icons.
- Background color is `#f9f9f9`, and it has padding.

#### Logo-side (`.logo-side`)
- The left part of the header containing the menu icon and the YouTube logo.
  - `display: flex;` makes it a flex container.
  - `align-items: center;` vertically centers items.

#### Logo-side i (`.logo-side i`)
- Styles the menu icon within the header.
  - `padding: 0 10px;` adds padding to the icon.
  - `cursor: pointer;` changes the cursor to a pointer on hover.

#### Logo-side img (`.logo-side img`)
- Styles the YouTube logo within the header.
  - `width: 50px;` sets the width of the logo.
  - `margin-left: 10px;` adds left margin for spacing.

#### Search-bar (`.search-bar`)
- Styles the search bar to input search queries.
  - `width: 40%;` sets the width.
  
#### Search-bar form (`.search-bar form`)
- Styles the form element within the search bar.
  - `height: 35px;` sets the height.
  - `display: flex;` makes it a flex container.
  - `border: 1px solid #ddd;` sets a border.

#### Search-bar input (`.search-bar input`)
- Styles the input field within the search bar.
  - `width: 95%;` sets the width.
  - `height: 100%;` sets the height.
  - `padding: 10px;` adds padding.
  - `margin: 0;` resets margin.
  - `border: none;` removes the border.

#### Search-bar button (`.search-bar button`)
- Styles the search button within the search bar.
  - `height: 100%;` sets the height.
  - `border: none;` removes the border.
  - `padding: 1% 2%;` adds padding.

#### Icons-side (`.icons-side`)
- Styles the right side of the header containing various icons.
- The icons are SVG images.
  - `width: 10%;` sets the width.
  - `display: flex;` arranges items horizontally.
  - `justify-content: space-between;` spaces them evenly.
  
#### Icons-side svg (`.icons-side svg`)
- Styles the individual icons within the icon-side.
  - `width: 24px;` sets the width.

### Side-bar (`.side-bar`)
- Styles the side-bar navigation menu.
- It includes two sections: "Main" and "Library."
- Background color is not specified.

#### Nav-items (`.nav-items`)
- Styles the container for navigation items.
  - `width: 100%;` sets the width.
  - `display: flex;` arranges items vertically.
  - `flex-direction: column;` arranges items in a column.
  - `margin: 15px 0;` adds top and bottom margin for spacing.

#### Nav-items .item (`.nav-items .item`)
- Styles individual navigation items.
  - `display: flex;` arranges items horizontally.
  - `align-items: center;` vertically centers items.
  - `padding: 15px 25px;` adds padding.

#### Nav-items .item span (`.nav-items .item span`)
- Styles the text within navigation items.
  - `margin-left: 15px;` adds left margin for spacing.
  - `color: #606060;` sets the text color.
  - `font-size: 14px;` sets the font size.

#### Nav-items .item:hover (`.nav-items .item:hover`)
- Styles navigation items on hover.
  - `background-color: #e5e5e5;` changes the background color.

### Videos Section (`.videos`)
- Styles the main content section where video thumbnails are displayed.
- Background color is `#f9f9f9`.
- `width: 85%;` sets the width.
- `height: 100%;` sets the height.
- `padding: 15px;` adds padding.
- `border-top: 1px solid #ddd;` adds a top border.

#### Videos h1 (`.videos h1`)
- Styles the "Recommend" heading.
  - `margin-bottom: 10px;` adds bottom margin for spacing.

#### Videos-wrapper (`.videos-wrapper`)
- Styles the container for video thumbnails.
  - `display: flex;` arranges items evenly.
  - `justify-content: space-around;` spaces items around evenly.
  - `flex-wrap: wrap;` allows items to wrap to the next row.

#### Video (`.video`)
- Styles individual video containers.
  - `width: 300px;` sets the width.
  - `margin-bottom: 30px;` adds bottom margin for spacing.
  - `box-shadow:0px 0px 15px -8px black;` adds a box shadow.

#### Thumbnail (`.thumbnail`)
- Styles the video thumbnail containers.
  - `width: 100%;` sets the width.
  - `height: 170px;` sets the height.

#### Thumbnail img (`.thumbnail img`)
- Styles the video thumbnail images.
  - `object-fit: cover;` maintains aspect ratio and covers the container.
  - `height: 100%;` sets the height.
  - `width: 100%;` sets the width.

#### Video Details (`.video_details`)
- Styles the container for video details.
  - `display: flex;` arranges items horizontally.
  - `padding: 2%;` adds padding.

#### Video Details Author (`.video_details .author`)
- Styles the container for the video author.
  - `border-radius: 50%;` makes it a circle.
  - `width: 15%;` sets the width.
  - `margin-right: 15px;` adds right margin for spacing.

#### Video Details Author img (`.video_details .author img`)
- Styles the author's profile image.
  - `height: 40px;` sets the height.
  - `width: 40px;` sets the width.

#### Video Details Content (`.video_details .content`)
- Styles the container for video content.
  - `width: 82%;` sets the width.

#### Channel Link (`.channel-link`)
- Styles the link to the video channel.
  - `text-decoration: none;` removes underlines.
  - `display: block;` makes it a block element.
  - `margin: 3% 0;` adds top and bottom margin for spacing.

