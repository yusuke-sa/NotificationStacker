# NotificationStacker
## 背景
- Android版のLineではグループラインの通知が最新１件しか見れない
- iOS版のように昔の通知も見えるようにしたい

## 実装方法(調査中)
- backgroundでNotificationListenerServiceで通知監視
- 通知が来たら、DBに保存(Room)
- アプリでDB内見れるようにList表示とか
- Widgetとかを作成しても面白そう

## 参考
- https://developer.android.com/reference/android/service/notification/NotificationListenerService
- https://developer.android.com/guide/topics/appwidgets?hl=ja
