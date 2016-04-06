This is the Logcat error I recieve when I press 'add revision task' in my 'Revision' activity. I am trying to get it so that in the 'tabview' in this activity, when I press the button, the second tab is updated with the data I have entered, by using 'listview_item1' 

    --------- beginning of crash
04-06 16:06:13.409    7123-7123/comepqtesting.wix.socot.epqtesting E/AndroidRuntime﹕ FATAL EXCEPTION: main
    Process: comepqtesting.wix.socot.epqtesting, PID: 7123
    java.lang.NullPointerException: Attempt to invoke virtual method 'android.text.Editable android.widget.EditText.getText()' on a null object reference
            at comepqtesting.wix.socot.epqtesting.Revision$1.onClick(Revision.java:58)
            at android.view.View.performClick(View.java:5198)
            at android.view.View$PerformClick.run(View.java:21147)
            at android.os.Handler.handleCallback(Handler.java:739)
            at android.os.Handler.dispatchMessage(Handler.java:95)
            at android.os.Looper.loop(Looper.java:148)
            at android.app.ActivityThread.main(ActivityThread.java:5417)
            at java.lang.reflect.Method.invoke(Native Method)
            at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
            at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
    --------- beginning of system


