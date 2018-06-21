
# Sparta-Advanced-Models-Lab-MVC

## Purpose
The purpose of this project was to build on my knowledge of Ruby on Rails models. I created models and controllers for seven different resources and made databases using mock data (Faker) as well as through entering the data myself on the ruby console. I used bootstrap and SASS to style the pages.



## Implementation
The funcitonality has been implemented using ruby on rails, bootstrap and SASS CSS.


#### Download
To download the code visit the github repo name Sparta-Advanced-Models-Lab-MVC and click the clone or download button to download as zip.
Alternatively the following command can be copied into the terminal:

```
git clone hub.com/isabelvalente/Sparta-Advanced-Models-Lab-MVC.git
```


## Challenges
The biggest challenge to this project was the incorporation of CSS through Bootstrap. I was also not aware that I needed to take extra steps to add images to pages as initially hard coding the image tag into the html did not work. I have included the code I used to make this work in the code snippets. I also learnt to use partials through creating an applications folder within the views folder for my navigation bar. I did this because the static page has a different navigation bar to the other pages.

## Snippets

I had to add this to the index.html.erb of the static page.

```
<head>
  <%= stylesheet_link_tag params[:controller] %>
</head>
```

I had to wrap the image url in <%= tags to make the image path work.

```
style="background-image: url('<%= asset_path 'book1.jpeg'%>')
```
