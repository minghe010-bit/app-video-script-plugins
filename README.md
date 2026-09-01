{
  "name": "app-video-script-plugins",
  "interface": {
    "displayName": "APP视频脚本插件"
  },
  "plugins": [
    {
      "name": "app-feature-update-video-script-generator",
      "source": {
        "source": "local",
        "path": "./plugins/app-feature-update-video-script-generator"
      },
      "policy": {
        "installation": "AVAILABLE",
        "authentication": "ON_INSTALL"
      },
      "category": "Productivity"
    }
  ]
}
