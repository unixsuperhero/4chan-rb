
/b/ thread archiver (OS X specific)


  Right now it takes some customization.

  line 41:

  * Change /Users/jtoyota/jearsh/pictures to the parent directory of your 4chan folder

  *Usage:*

  All it really needs is the thread id, these 2 use the thread id as the folder name:

    $> ./4chan.rb 1234567778

  It extracts the id from the url, if you paste the whole thing:

    $> ./4chan.rb boards.4chan.org/b/res/1234567778

  Use a custom folder name:

    $> ./4chan.rb boards.4chan.org/b/res/1234567778 foldername


