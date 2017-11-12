# Android-Push-Notifications
Here we make use of Notification Manager, Pending intents, Notification.class to pop a push notifications.



A PendingIntent is a token that you give to a foreign application (e.g. NotificationManager, AlarmManager, Home Screen AppWidgetManager, or other 3rd party applications), which allows the foreign application to use your application's permissions to execute a predefined piece of code.

If you give the foreign application an Intent, and that application sends/broadcasts the Intent you gave, they will execute the Intent with their own permissions. But if you instead give the foreign application a PendingIntent you created using your own permission, that application will execute the contained Intent using your application's permission.
