---
id: version-0.26-modal
title: Modal
original_id: modal
---

A Modal component covers the native view (e.g. UIViewController, Activity) that contains the React Native root.

Use Modal in hybrid apps that embed React Native; Modal allows the portion of your app written in React Native to present content above the enclosing native view hierarchy.

In apps written with React Native from the root view down, you should use Navigator instead of Modal. With a top-level Navigator, you have more control over how to present the modal scene over the rest of your app by using the configureScene property.

### Props

* [`animationType`](modal.md#animationtype)
* [`onRequestClose`](modal.md#onrequestclose)
* [`onShow`](modal.md#onshow)
* [`transparent`](modal.md#transparent)
* [`visible`](modal.md#visible)
* [`animated`](modal.md#animated)

---

# Reference

## Props

### `animationType`

| Type                          | Required |
| ----------------------------- | -------- |
| enum('none', 'slide', 'fade') | No       |

---

### `onRequestClose`

| Type                                                                   | Required |
| ---------------------------------------------------------------------- | -------- |
| Platform.OS === 'android' ? PropTypes.func.isRequired : PropTypes.func | No       |

---

### `onShow`

| Type     | Required |
| -------- | -------- |
| function | No       |

---

### `transparent`

| Type | Required |
| ---- | -------- |
| bool | No       |

---

### `visible`

| Type | Required |
| ---- | -------- |
| bool | No       |

---

### `animated`

**Deprecated.** Use the `animationType` prop instead.

| Type | Required |
| ---- | -------- |
| bool | No       |
