#cloud dialog is for 如数科技
###how to init a dialog

```javascript
var d = new CloudDialog({
    quickClose: false,
    ok: function  () {
        debugger
    },
    okValue: 'ok',
    buttons: [{
        text: 'dddd',
        disabled: true,
        handler: function  () {
            alert(1)
        }
    }, {
        text: 'dsdfdfn你啊当时的',
        handler: function  (e) {
            debugger
        }
    }]
})
d.showModal()
```

###options (the values are default)

```javascript
{
	title: '',
	quickClose: false,
	content: '确认要删除当前报销单模版?',
	width: 240,
	className: 'text-align',
	buttonAlign: 'center',
	buttons: [
		 
	],
	ok: null,
	cancel: null,
	onShow: function  () {
	},
	onHide: function  () {
	},
	onDestroy: function  (argument) {
		
	},
	okDisabled: false,
	okValue: '',
	cancelDisabled: false,
	cancelValue: ''
}
```