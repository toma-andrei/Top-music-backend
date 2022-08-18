# Top-music-backend

Social network for music - personal project

DATABASE:

Users(id(pk), username, password, real_name, description, admin_right, song_add_right, profile_pic, comment_right, reaction_right, banned)
Songs(id(pk), added_by (fk), name, artists (csv), description, link)
Artists(id(pk), name)
Reactions(song_id (fk), user_id(fk), type_of_reaction)
Comments(id(pk), user_id(fk), song_id(fk), comment)

TODO
Replies(comment_id(fk), user_id(fk), reply)
