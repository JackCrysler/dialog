## 使用ES6 class 创建dialog提示框组件

	* 调用方法：

		const DialogCase = new Dialog();

			DialogCase.show({
                title: 'popular modal',
                info: '这是我的第一个class创建实例',
                callback: function (reback) {
                    console.log(reback)
                }
            })

        const AwsomeDialogCase = new AwsomeDialog();

        	AwsomeDialogCase.show({
                title: 'awsome modal',
                info: '这是我的第一个class extends创建实例',
                callback: function (reback) {
                    console.log(reback)
                }
            })