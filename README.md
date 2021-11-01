# Music_fetcher_tools

Ensemble of small jupyter notebooks fetching music-related information on your favorite artists through popular APIs (itunes, billboard).

**BillBoardArtists_Fetcher** : Extract the artists present in the Billboard hot-100 list over a specified period of time, including the featuring artists.  

**AlbumCovers_Fetcher.ipynb** : Extract all the album covers of a specified artist from the Itunes API. 

    1. Fetches from the itunes API the artwork of all albums, mixtapes and compilations image 
    covers from an artist with name artistName,
    (avoiding all other projects or singles as much as possible),
    2. Download covers as jpeg,
    3. Place covers in "Album_Covers" folder, as Artist_AlbumName_AlbumGenre.jpg
    
