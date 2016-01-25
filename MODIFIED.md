### vinsonxiao 2015.11.14修改
line 10671, 函数requestError, 当timeout时，xhr.onabort被触发，此时将错误码改为408，而不是-1。