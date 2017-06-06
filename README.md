# robovm-notification
Making Robovm push Notification from facebook-notification

In Gralde File add this line
1) Config  Notification framework to project
add this line to Gradle file
compile "com.mobidevelop.robovm:robopods-facebook-ios:$robopodsVersion"
add framwork FBNotifications.framwork to libs folder in ios project 
add config to robovm.xml file 
        <framework>FBNotifications</framework> 


<exportedSymbols>
        <symbol>FB*</symbol>
        <symbol>kFB*</symbol>
    </exportedSymbols>
