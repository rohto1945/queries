  - **SQLite queries**
    
      - **Browsers**
        -  Mozilla Firefox *61+*:
            - [firefox_places.sql](https://github.com/kacos2000/queries/blob/master/firefox_places.sql) 
            - [firefox_favicons.sql](https://github.com/kacos2000/queries/blob/master/firefox_favicons.sql) 
            - [firefox_formhistory.sql](https://github.com/kacos2000/queries/blob/master/firefox_formhistory.sql) 
            - [firefox_contentprefs.sql](https://github.com/kacos2000/queries/blob/master/firefox_contentprefs.sql) 
      
        - Opera *54+*
          - [Opera_History.sql](https://github.com/kacos2000/queries/blob/master/Opera_History.sql)
          - [Chrome_favicons.sql](https://github.com/kacos2000/queries/blob/master/chrome_favicons.sql) *(works with Opera as well)*
      
        - Chrome *67+*
          - [Opera_History.sql](https://github.com/kacos2000/queries/blob/master/Opera_History.sql) *(works with Chrome as well)*
          - [Chrome_favicons.sql](https://github.com/kacos2000/queries/blob/master/chrome_favicons.sql)

      
       - **Skype**  *(version 7.21 & 7.41 dBs)*    
       
           - [skype_main.sql](https://github.com/kacos2000/queries/blob/master/skype_main_db.sql)<br>
             Query Skype's *(Classic)* main.db for chats & file transfers.<br>
             
           - [skype_cache_db](https://github.com/kacos2000/queries/blob/master/skype_cache_db.sql)<br>
             Query Skype's *(Classic)* both cache_db.db databases found at AppData\Roaming\UserProfile\media_messaging\ <br>
             - 'emo_cache_v2\asyncdb\cache_db'   *(cached Emoticons etc)* & <br> 
             - 'media_cache_v3\asyncdb\cache_db' *(Cached Sent & Received images)* folders.<br>
                     
           - [PowerShell script/sqlite query](https://github.com/kacos2000/queries/blob/master/cache_db.ps1) so that you can view the Hex Blob output<br>
             - [Sample Output (csv)](https://github.com/kacos2000/queries/blob/master/cache_db.csv)<br><br>



       - **Google Drive**   <br>     
             Query Google Drive's [snapshot.db](https://github.com/kacos2000/queries/blob/master/GDrive_snapshot.sql) found at the '%username%\AppData\Local\Google\Drive\user_default' folder  .<br>      
