# Music_fetcher_tools

Ensemble of small jupyter notebooks fetching music-related information on your favorite artists through popular APIs (itunes, billboard).

**BillBoardArtists_Fetcher** : Jupyter notebook containing a function which extracts the artists present in the Billboard hot-100 list over a specified period of time, including the featuring artists. Tests the function with examples. 

**AlbumCovers_Fetcher.ipynb** : Jupyter notebook containing a function which extracts all album covers of a specified artist from the Itunes API. Tests the function with examples. Specifically, the ExtractAlbumCovers function:

    1. Fetches from the itunes API the artwork of all albums, mixtapes and compilations image 
    covers from an artist with name artistName,
    (avoiding all other projects or singles as much as possible),
    2. Download covers as jpeg,
    3. Place covers in "Album_Covers" folder, as Artist_AlbumName_AlbumGenre.jpg
    
