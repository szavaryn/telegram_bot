# telegram_bot
Simple solution for matching data from primary lists and forwarded messages. Volunteer's project for finding people in Belarusian prisons.

Over fifty thousands people in Belarus have been arrested during last two years due to their political position. Even now dozens are appeared in prison every day. Police never tells names of apprehended as well as any details related to current status and location of prisoners. In this case your family and friends wouldn't know even where you are.

Since 08.2020 huge number of volunteers have been collecting the information and regularly post it in Telegram channels. Almost every day lists with data of recently arrested people are published. 

Sometimes you take a look at such lists and attempt to find someone whom is known for you: relatives, friends, colleagues, schoolmates, etc. It could be extremely useful in case if you are able to sent some food and clothes or help somehow the prisoner's family.

I've created fast solution of very simple Telegram bot for matching data row per row by names and surnames:
- You need to list surname, name, patronymic and birth year of all persons you are interested it to separate .csv;
- Load it to local database;
- Forward a message from Telegram channels of volunteers;
- Notice the result: the pairs of matched rows, one from your list and another from list of prisoners. 
