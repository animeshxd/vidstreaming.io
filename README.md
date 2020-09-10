## My Vidstreaming.io watch Manager (termux/linux)
  - added next function for anime 
  - watch last watched anime
  - save watched list inside ./myAnime/savelist.txt
## Anime url help: (Enter Anime url:)
  - Type 'o' to watch last watched anime
  - _https://vidstreaming.io/videos/shichinin-no-nana-episode-26_  remove last numbers like https://vidstreaming.io/videos/shichinin-no-nana-episode- and paste
  - Type 'exit' to exit the program
## Anime episode help: (Enter Episode number)
  - Type episode no to watch that episode like `Enter Episode number 1`
  - Type 'n' to watch next episode
  - Type 'exit' to enter url again
  
  
  `# webbrowser.open(f"{vids}{open3}{watched_ep}")`
  
  `os.system(f"termux-open-url {vids}{open3}{watched_ep}")`
