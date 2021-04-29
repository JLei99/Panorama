# Panorama_stitching
Takes two pictures with common sections and stitches them together.
- Uses feature detection to find the matching points.
- Uses RANSAC to estimate Homography from matched pairs of points.
- Uses boundary distance transforms to blend images in to the reference frame.

Here is a sample result:
Two pictures before stitching:

![left](https://user-images.githubusercontent.com/82390464/116490239-db0a1880-a864-11eb-9658-4159a1268a59.jpg)
![right](https://user-images.githubusercontent.com/82390464/116490252-e5c4ad80-a864-11eb-92ef-a646b0a2b4e2.jpg)

The result after stitching:\
![Screen Shot 2021-04-28 at 9 04 05 PM](https://user-images.githubusercontent.com/82390464/116490407-4eac2580-a865-11eb-8df8-b5bd14beb98f.png)

