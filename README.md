# cordova-plugin-x-toast
 with cordova-plugin-themeablebrowser

#example
cordova.toast.showWithOptions({
    message: '페이지로딩중입니다...', duration: 3000, position: 'center',
    styling: { opacity: 1, backgroundColor: '#3399EE', textColor: '#FFFFFF', textSize: 12, cornerRadius: 20,
        shadow : {
            color : '#000000',
            opacity: .8,
            radius: 6.0,
            offset: { x: 4, y: 4},
        },
        android_shadow: 6,
    }
});