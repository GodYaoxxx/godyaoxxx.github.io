---
# 只保留这一行元数据，专门给区块读取头像
avatar: "avatar.jpg"
title: "吴昌进"
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: wuchangjin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: 下载完整简历
        url: uploads/wuchangjin-cv.pdf
      headings:
        about: '职业简介'
        education: '教育经历'
        interests: '研究方向'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
---
