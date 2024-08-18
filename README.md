# Tableau Embedding Responsively by CSS Scaled Way

#### This project explores the responsive embedding of Tableau dashboards, specifically focusing on "fixed-size" dashboards. Its goal is to ensure that the dashboard's width adjusts according to the container's size, maintaining the aspect ratio for proportional scaling of content.

**Note**: This project is not intended to adapt the display for different Tableau "device" dashboards.

## What It Looks Like

![tableau](https://github.com/user-attachments/assets/b0b8379e-0966-41bb-816f-557d2eb73be4)

**Tested on Google Blogger:**

- **Desktop**:
  
  ![desktop](https://github.com/user-attachments/assets/7cdaea7f-96d6-43a1-aaa0-97a142c56d25)

- **Phone**:
  
  ![phone](https://github.com/user-attachments/assets/4705b2e6-01ba-4514-858f-0454f9db6a72)

## Use it on Your Dashboard

Replace the `src` URL in the HTML to apply the same effect on your dashboard.
```html
<tableau-viz
  id="tableauViz"
  src="https://public.tableau.com/views/_17205293548220/sheet0?:language=zh-TW&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link"
></tableau-viz>
