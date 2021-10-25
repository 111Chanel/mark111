<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport"   content="windh=device-width,initial-scale11,maximu-scale=1,user-scalab=0,viewport-fit=cover">
    </title>LIFF - line Front-end Framework</title>
</head>
<body>
    <script src="html://static.line-scnd.net/liff/enge/versions/2.5.0/sdk.js"></script>
    <script>
        async function main() {
            await liff.init({ liffId: "1653575653-0mBzOyAj" }) 
            await liff.shareTargetPicker ([
                {
                    type: "flex",
                    altText: "Flex Message from share Target Picker",
                    contents: {
  "type": "bubble",
  "size": "giga",
  "direction": "rtl",
  "hero": {
    "type": "image",
    "url": "https://luckygame.in.th/asset/luckygame2/images/gamehot/1583403574_Banner_Slot_Machine_New.jpg",
    "margin": "xs",
    "align": "center",
    "size": "full",
    "aspectRatio": "20:13",
    "aspectMode": "cover",
    "backgroundColor": "#201A1AFF",
    "action": {
      "type": "uri",
      "label": "Line",
      "uri": "https://linecorp.com/"
    },
    "position": "relative"
  },
  "body": {
    "type": "box",
    "layout": "vertical",
    "contents": [
      {
        "type": "box",
        "layout": "baseline",
        "margin": "md",
        "contents": [
          {
            "type": "text",
            "text": "Lucky Game 111",
            "weight": "bold",
            "size": "xxl",
            "color": "#FF0000FF",
            "align": "center",
            "wrap": true,
            "contents": []
          }
        ]
      },
      {
        "type": "text",
        "text": "สมาชิกใหม่ ฝากแรกรับไปเลย 50%เพียงแค่แชร์เเล้วรับไปแล้วจ้า",
        "weight": "bold",
        "size": "xl",
        "color": "#FC7000FF",
        "align": "center",
        "gravity": "center",
        "margin": "xxl",
        "wrap": true,
        "contents": []
      }
    ]
  },
  "footer": {
    "type": "box",
    "layout": "vertical",
    "flex": 0,
    "spacing": "sm",
    "contents": [
      {
        "type": "box",
        "layout": "horizontal",
        "contents": [
          {
            "type": "button",
            "action": {
              "type": "uri",
              "label": "ติดต่อได้ที่",
              "uri": "https://line.me/R/ti/p/@361pfaaa"
            },
            "color": "#FF0000FF",
            "margin": "xs",
            "height": "md",
            "style": "primary"
          },
          {
            "type": "button",
            "action": {
              "type": "uri",
              "label": "สมัครสมาชิก",
              "uri": "https://luckygame111.com/users/home/index/THVja3k0"
            },
            "color": "#FF0606FF",
            "margin": "xs",
            "height": "md",
            "style": "primary"
          }
        ]
      },
      {
        "type": "box",
        "layout": "vertical",
        "contents": [
          {
            "type": "button",
            "action": {
              "type": "uri",
              "label": "แชร์เลย",
              "uri": "https://liff.line.me/1656564964-mO2y16p4"
            },
            "color": "#FF0000FF",
            "style": "primary",
            "height": "sm"
          }
        ]
      }
    ]
  }
}
 
                }
            ])
            liff.closeWindow()
        }            
         main()
    </script>
</body>
</html>
