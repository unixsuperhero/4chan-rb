
/b/ thread archiver (OS X specific)


  Right now it takes some customization.

  line 41:

  * Change /Users/jtoyota/jearsh/pictures to the parent directory of your 4chan folder

  *Usage:*

  Use the thread id as the folder name:

  * All it really needs is the thread id, to archive the page

      $> ./4chan.rb 1234567778

  * Or it can extract the id from the url, if you paste the whole thing:

      $> ./4chan.rb boards.4chan.org/b/res/1234567778

  * Or use a custom folder name:

      $> ./4chan.rb 1234567778 foldername


