---
title: Bazel - Windows on Arm
name: Bazel
logo: /assets/images/content/windows_on_arm/Bazel.png
description: >
  Bazel is an open-source build and test tool that scalably supports multi-language and multi-platform projects. Bazel is used for many popular projects and is the only support build platform for popular frameworks like TensorFlow.
image: /assets/images/content/iStock-667012914_sm.jpg
jumbotron:
  class: header_2021_2 theme_banner
  title_row: true
  title: Windows on Arm Project - Bazel
  image: /assets/images/content/iStock-667012914_sm.jpg
links:
  - text: Releases
    url: https://github.com/bazelbuild/bazel/releases
  - text: Enablement Notes
    url: https://linaro.atlassian.net/wiki/spaces/WOAR/pages/28685041907/Bazel
flow:
  - row: container_row
    style: #
    sections:
      - format: custom_include
        source: woa/project_page_content.html
  - row: container_row
    style: my-3 bg-light-gray
    sections:
      - format: custom_include
        source: woa/projects.html
  - row: container_row
    style: #
    sections:
      - format: two_column
        style: #
        breakpoint: md
        left_column:
          custom_size: 8
          style: p-3
          text: |
            **Provide feedback or request support for a missing package**
        right_column:
          custom_size: 4
          style: p-3
          button:
            style: blue-button
            title: Linaro Service Desk
            url: https://linaro-servicedesk.atlassian.net/servicedesk/customer/portal/22/group/85/create/301
  - row: container_row
    style: my-3 bg-light-gray
    sections:
      - format: title
        style: text-left white-border-title font-weight-bold
        title_content:
          size: h3
          style: font-weight-bold
          text: Linaro Windows on Arm Technical Meetings
      - format: title
        style: text-left font-weight-bold
        title_content:
          size: h3
          style: font-weight-bold
          text: Windows on Arm Technical
      - format: text
        style: text-left
        text_content:
          text: |
            Every two weeks on Tuesday - 4:00-5:00pm (GMT+1) <br/>
            If you're interested in participating in the meeting, please contact windowsonarm@linaro.org
  - row: container_row
    style: my-3
    sections:
      - format: title
        style: text-left white-border-title font-weight-bold
        title_content:
          size: h3
          style: font-weight-bold
          text: Active Members
      - format: custom_include
        source: woa/members.html
---

Bazel is an open-source build and test tool that scalably supports multi-language and multi-platform projects. Bazel is used for many popular projects and is the only support build platform for popular frameworks like TensorFlow.

Windows on Arm support is available from Bazel v5.1

> Note: Bazel v5.1 is not yet released. Bazel v6.0 pre-releases are available for windows on arm.
