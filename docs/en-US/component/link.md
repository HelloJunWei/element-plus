---
title: Link
lang: en-US
---

# Link

Text hyperlink

## Basic

Basic text link

:::demo

link/basic

:::

## Disabled

Disabled state of link

:::demo

link/disabled

:::

## Underline

Underline of link

:::demo

link/underline

:::

## Icon

Link with icon

:::tip

Use the `icon` attribute to add icon. You can pass either string for the component name (registered in advance) or the component itself which is a SVG Vue component. Element Plus has provided a set of icon that you can find at [icon](/en-US/component/icon)

:::

:::demo

link/with-icon

:::

## Attributes

| Attribute | Description                         | Type                                   | Accepted Values                                       | Default |
| --------- | ----------------------------------- | -------------------------------------- | ----------------------------------------------------- | ------- |
| type      | type                                | string                                 | primary / success / warning / danger / info / default | default |
| underline | whether the component has underline | boolean                                | —                                                     | true    |
| disabled  | whether the component is disabled   | boolean                                | —                                                     | false   |
| href      | same as native hyperlink's `href`   | string                                 | —                                                     | -       |
| icon      | icon component                      | `string \| Component \| (() => VNode)` | —                                                     | -       |

## Slots

| Name | Description               |
| ---- | ------------------------- |
| —    | customize default content |
| icon | customize icon component  |
