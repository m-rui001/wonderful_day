# INFO

These files are parsed in `Speaker: Dialogue` format. Narration often enclosed in Asterisks.


# Notes:

- **AIR**: Different chapters seem to be separated via these indicators:
```
..........
.......
....
```
- **Aokana**: H-scenes included, extras missing  
- **Bokuten - Why I Became an Angel**
   - Some files skipped due to problems with the converter utility or the script
   - Script used `<i>` `</i>` for italics; converted to Markdown underscores `_`
- **Cho Dengeki Stryker** - One script file missing (4_05_050) due to dictionary key missing from VNTranslationTools
- **Comyu - Kuroi Ryuu to Yasashii Oukoku**: Dialogs enclosed in quotation marks, actions not enclosed
- **CLANNAD**: Very minor issues with words triggering Dangopedia entries missing from the script and linebreaking - 264 instances in the whole file 
- **Cross Worlds**: Narrator as a character
- **DRACU-RIOT!**: some files had to be skipped since they were in Japanese
- **euphoria**:
   - By necessity, dialogs are surrounded by double quotes
   - Some script files omitted (not many, but should not be important for the sake of the trainin data)
- **Fxxx Me Royally!! Horny Magical Princess (Himetai)**: script files manually reordered
- **Girls Frontline**:
   - _Is this actually relevant for good Waifu training data? Is so much text from this game desirable?_
   - Extras have been placed as a separate file
   - Needs cleaning for:
      - Chinese character names
      - Malformed HTML tags
      - Too short sections that don't add much information
      - Dialogues in Chinese that might have been missed.
- **Hoshizora no Memoria**: changed character name "You" to "Kogasaka You" (full name) to avoid issues with Pygmalion
- **[Nurse Love Addiction](https://vndb.org/v16610)** / **[Nurse Love Syndrome](https://vndb.org/v7301)**:
   - Source files were in binary format, required too much manual work and finetuning to be properly parsed
- **Saku Saku (Koi ga Saku Koro Sakura Doki)**: Minor manual cleaning involved
- **[Rewrite](https://vndb.org/v751)**:
   - Dialogues enclosed by double quotes, narration not enclosed, actions enclosed by asterisks
   - Special dialogues (telepathy, etc) which used Japanese thick angle brackets `『`/`』` have been replaced with `«`/`»`
   - May need further cleaning but it seems mostly ok
   - Manual removal of extra data from script files and garbage script files was performed
- **Sharin no Kuni, Yuukyuu no Shounenshoujo**: Minor manual cleaning involved
- **The Fruit of Grisaia**: Dates & Narration labelled  
- **The Labyrinth of Grisaia**: Dates & Narration labelled  
- **The Eden of Grisaia**: Dates & Narration labelled
- **The Shadows of Pygmalion (Negai no Kakera to Hakugin no Agreement)**: Minor issues due to encoding errors in the source files
- **Wonderful Everyday - Discontinuous Existence (Subarashiki Hibi)**
   - The script uses narration for citing "on-screen" elements that characters read (emails, text)
