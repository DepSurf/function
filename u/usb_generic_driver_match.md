# Function: <code>usb_generic_driver_match</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff818cffb0)
Location: drivers/usb/core/generic.c:215
Inline: True
```
**Symbols:**

```
ffffffff818cffb0-ffffffff818cffe7: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff818da4f0)
Location: drivers/usb/core/generic.c:211
Inline: True
```
**Symbols:**

```
ffffffff818da4f0-ffffffff818da527: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff818bd950)
Location: drivers/usb/core/generic.c:211
Inline: True
```
**Symbols:**

```
ffffffff818bd950-ffffffff818bd987: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81953c90)
Location: drivers/usb/core/generic.c:211
Inline: True
```
**Symbols:**

```
ffffffff81953c90-ffffffff81953cc7: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81aad2a0)
Location: drivers/usb/core/generic.c:211
Inline: False
```
**Symbols:**

```
ffffffff81aad2a0-ffffffff81aad2ef: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81c34ba0)
Location: drivers/usb/core/generic.c:211
Inline: False
```
**Symbols:**

```
ffffffff81c34ba0-ffffffff81c34bef: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81c9bec0)
Location: drivers/usb/core/generic.c:211
Inline: False
```
**Symbols:**

```
ffffffff81c9bec0-ffffffff81c9bf0f: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool usb_generic_driver_match(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/generic.c (ffffffff81d50dc0)
Location: drivers/usb/core/generic.c:227
Inline: False
```
**Symbols:**

```
ffffffff81d50dc0-ffffffff81d50e0f: usb_generic_driver_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
