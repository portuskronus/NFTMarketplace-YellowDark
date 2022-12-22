Hi there, 
I have uploaded this to show you a working example of a complex front end. It is still a work on progress so some things are glitchy as mentioned below but you'll get a gist of the scope of work when it comes to front end.

Thanks!!
Parik Ahlawat


BUGS TO FIX

- Whole page overflow / not mobile responsive.

- The 'Create' yellow button in the navbar is not showing the word 'Create'. components/Navbar/NavBar.jsx line 131.

- Discover and Help Center (Navbar) they need to close when you click on them again. components/Navbar/Discover and components/Navbar/HelpCenter.

- Top Creators List -main page- is overlapping each other. components/FollowerTab/FollowerTabCard.module.css

- Explore NFTs Video. -main page- The framer-motion dependency is not working. components/Slider/SliderCard.jsx.

- Featured NFTs -main page- not showing the images. components/NFTCard/NFTCard.jsx.

- The Videos -main page- not displaying the correct box and image size. components/Video/Video.module.css.

- Collection Page, inside Discover: the image on the top is not in a good size(probabbly because of the general overflow). collectionPage/Banner/Banner.jsx.

-Same with Search, inside Discover. SearchPage/SearchBar/SearchBar.jsx.

- NFTDetails Page -inside Discover- in the description next to the price, the '96 in stock' span is overlapped.  NFTDetailsPage/NFTDescription/NFTDescription.jsx.



