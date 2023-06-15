# Music App

## Description

- It is a Spotify-like app, which contains albums, tracks, and playlists.
- Each album should have an artist.
- Only authenticated users can able to favorite/unfavourite tracks.
- Admin panel used to add and manage data by admins
- Website provides an interactive UI for the user to use our music app

### Application will have two types of users :

- Admin - Should have Read/Write access
- User - Should have Read access only, except Favourite/Unfavourite functionality

**Note:** Admin is also a user. Admin should have all access the same as the user. Additionally, they can modify the content.

## Models

* Artist
    - id
    - name
    - image_url
    - created_at
    - updated_at

* Album
    - id
    - name
    - description
    - image_url
    - published_at
    - is_published
    - artist_id
    - created_at
    - updated_at

* Track
    - id
    - name
    - index
    - track_url
    - image_url
    - album_id
    - is_published
    - created_at
    - updated_at

* Playlist
    - id
    - name
    - description
    - image_url
    - is_published
    - created_at
    - updated_at

* Favourite-tracks
    - id
    - track_id
    - user_id
    - index
