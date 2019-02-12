# RuntimeExchangeMethod
利用runtime hook 系统方法，\n
1.UIControl (Extension)拦截所有的按钮点击事件sendAction:to:forEvent:并进行处理\n
2.NSMutableArray (Extension)拦截insertObject:atIndex:方法，避免为空\n
3.NSMutableDictionary (Extension)拦截 setObject:forKeyedSubscript:方法，避免key为空，拦截objectForKeyedSubscript:进行处理
