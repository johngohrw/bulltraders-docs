+++
title = 'Editing Content'
weight = 2
+++

# Editing Content

## General Content

If you want to change any content on this website, unless explicitly stated on this page, the steps would probably be the following:

1. Make sure you're logged into Wordpress admin, then visit the page that you want to edit.
2. Click on the "Edit with Elementor" on the top header bar.

   ![alt text](/editwelementor.png)

3. Scroll to the section that you want to edit, click on it.

   ![alt text](</Screenshot 2024-05-08 at 3.48.57 PM.png>)

4. Edit the content on the left sidebar editor. Remember to click "Update" when you're done.

   ![alt text](</Screenshot 2024-05-08 at 3.50.10 PM.png>)

## Site Header Menu

![alt text](</Screenshot 2024-05-08 at 3.56.48 PM.png>)

1. Head to the Wordpress Admin Dashboard, then click on `Appearance` > `Customize` on the sidebar. It will take you to [this page](https://bulltraders.com.my/wp-admin/customize.php).
2. Click on `Menu` > `Primary Menu`.
3. You may change the URL and Navigation Label and reorder as you wish.

## Site Footer

![alt text](</Screenshot 2024-05-08 at 3.58.09 PM.png>)

1. Head to the Wordpress Admin Dashboard, then click on `Appearance` > `Customize` on the sidebar. It will take you to [this page](https://bulltraders.com.my/wp-admin/customize.php).
2. Click on `Footer Builder`.
3. The text content on the left can be edited by clicking on `Widget 1`.
4. The Google Maps Embed on the right can be edited by clicking on `HTML 1`. By clicking on the `Text` tab on the editor, you will be able to see the embed link.

## Bottom CTA Section (Before Site Footer)

![alt text](/bottomCTA.png)

1. Head to the Wordpress Admin Dashboard, then click on `Appearance` > `Elementor Header & Footer Builder`.
2. Under `Site CTA Before Footer, with top content padding`, click on `Edit with Elementor`
3. Click on the content on the right, until you see `Edit Template` shows up on the left sidebar like this:

   ![alt text](</Screenshot 2024-05-08 at 4.07.52 PM.png>)

4. Click on `Edit Template`

5. Edit and Update!

   ![alt text](</Screenshot 2024-05-08 at 4.09.25 PM.png>)

## Home Carousel

![alt text](</Screenshot 2024-05-08 at 2.21.35 PM.png>)

1. Head to the [homepage](https://bulltraders.com.my/), click on "Edit with Elementor" on the top header.

2. Click on the carousel section.
   ![alt text](</Screenshot 2024-05-08 at 2.18.39 PM.png>)

3. You may now edit the slides content on the sidebar.
   ![alt text](</Screenshot 2024-05-08 at 2.20.09 PM.png>)

## Creating new `product` Posts to display under `Services` page.

![alt text](</Screenshot 2024-05-08 at 4.16.54 PM.png>)

The `product` posts you see on `Services` page can be clicked into. In case you want to create such new `product` posts, heres how to do it:

1. Head to the Wordpress Admin Dashboard, then click on `Posts` > `Add New`.

2. This will take you to the Wordpress Editor page. Go ahead and give it a Title and write your Content.

3. Next, we want to make sure our product is marked as `product` under `Categories`.

   ![alt text](</Screenshot 2024-05-08 at 4.57.20 PM.png>)

   This ensures that it will be considered as a product under `Services` page.

4. **Important**: When you're finished, make sure to summarize your product under `Excerpt`, and give it a `Featured Image`. This makes sure it's displayed properly if included in `Services` Page.

   ![alt text](</Screenshot 2024-05-08 at 5.00.49 PM.png>)

5. Save and Publish! If you want to include it as a Featured Product item in `Services` Page, take look at the next section.

## Featured Product Items in "Services" Page

![alt text](</Screenshot 2024-05-08 at 4.16.54 PM.png>)

You might want to feature a different set of products here on `Services` page, so here's how:

1. Head to the [services page](https://bulltraders.com.my/services), click on "Edit with Elementor" on the top header.
2. Click on the content until you see `Edit Loop Grid` on the left sidebar.

   ![alt text](</Screenshot 2024-05-08 at 4.18.57 PM.png>)

3. Click on `Query`. This is the default settings that will pick 3 of the latest posts under `product` Category.

   ![alt text](</Screenshot 2024-05-08 at 4.20.47 PM.png>)

4. To customize this, just select `Manual Selection` under `Source`

   ![alt text](</Screenshot 2024-05-08 at 4.28.11 PM.png>)

5. Now, under `Search & Select`, you can actually search and pick the exact post that you want to feature under this section.

   ![alt text](</Screenshot 2024-05-08 at 4.28.11 PM.png>)

6. You can keep searching and fill it up until you reach the desired number of products you want to show.

   ![alt text](</Screenshot 2024-05-08 at 4.31.45 PM.png>)

7. Double check how it looks and remember to save!

## Gallery Images

![alt text](/gallery.png)

1. Make sure you're logged into Wordpress admin. Go to https://bulltraders.com.my/gallery/. Click on `Edit with Elementor`.
2. Click on the Gallery Grid on the right, until `Edit Gallery` shows up on the right.

   ![alt text](</Screenshot 2024-05-08 at 5.19.51 PM.png>)

3. Click on the Pen icon

   ![alt text](</Screenshot 2024-05-08 at 5.20.52 PM.png>)

4. Proceed to upload and select your own pictures on the uploader.
5. Remember to click `Update`.

## Featured Youtube Videos

It was actually quite difficult to automatically fetch the latest videos from your channel (YouTube API restrictions are making it hard). So I had to fallback to a more manual method of maintaining our list of Featured YouTube Videos here.

1. Make sure you're logged into Wordpress admin. Go to https://bulltraders.com.my/gallery/. Click on `Edit with Elementor`.

2. Click on the `Featured Videos` section until you see `Edit Custom HTML` on the left sidebar.

   ![alt text](</Screenshot 2024-05-08 at 5.25.17 PM.png>)

3. Each block of code here corresponds to each video that you want to feature in that order.

   ![alt text](</Screenshot 2024-05-08 at 5.26.47 PM.png>)

4. You may replace any of those with the embed code of the new video. To get the embed code, go to the new video on YouTube, and click on `Share`:

   ![alt text](</Screenshot 2024-05-08 at 5.28.10 PM.png>)

5. Click on Embed

   ![alt text](</Screenshot 2024-05-08 at 5.31.47 PM.png>)

6. Copy all the code from the right side.

   ![alt text](</Screenshot 2024-05-08 at 5.32.30 PM.png>)

7. Replace **one** of the existing code block with the newly-copied code.

   ![alt text](</Screenshot 2024-05-08 at 5.34.53 PM.png>)

8. Click `Update`.
