# android-jdwp
debug android app from command

  adb forward tcp:8618 jdwp:785 --- adb forward local jdwp:(remote pid)

  jdb -sourcepath xxxxxx -connect com.sun.jdi.SocketAttach:hostname=localhost,port=8618
  
  use help, see basic commands
  
  &gt; help  
