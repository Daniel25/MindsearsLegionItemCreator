Make a new database named dbc or db2 and execute these sql files into the newly created db.  
  
  
These are six tables which I extracted from Legion db2 files  
https://github.com/mindsear/MindsearsLegionItemCreator/releases/download/v2.0/legion_sql_tables.rar containing the following tables:  
  
Emotes_db2.sql  
faction_db2.sql  
item_appearanceID.sql  
ItemSparse_db2.sql  
legion_icons.sql  
spellitemenchantment_db2.sql  
  
  
  
-- legion_icons.sql --------------------------------
-- 
-- Icon ID's + Names
-- Icon Id's were taken from Item.db2 (TrinityCore Legion 7.2.5)
-- Names were pulled from wowhead (using a custom application)
--
-- Execute a query like the following into your database so you can search icons with ease
-- For example you can search like this: [B]SELECT * FROM legion_icons WHERE IconName LIKE '%poison%';
-- and you will get every icon containing the "poison" word
-- 
-- --------------------------------------------------------
