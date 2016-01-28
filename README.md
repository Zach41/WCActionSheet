#WCActionSheet

这是一个仿微信ActionSheet的一个小demo

###Usage

```objective-c
WCActionSheet *actionSheet = [[WCActionSheet alloc] initWithTitle:@"XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXxxxxxxxxXXXXXXXXXXXXXXXXXXXXXXX" delegate:self cancelButtonTitle:@"Cancel" destructiveButtonTitle:@"Desctructive" otherButtonTitles:@[@"Hello", @"Haha"]];

[actionSheet showInView:self.view];

```

WXAction有一个Delegate方法，用来在按钮被点击时作为回调调用

```objective-c
- (void)WCActionSheet:(WCActionSheet *)actionSheet clickButtonOnIndex:(NSInteger)index;
```
