# Function: <code>usb_set_device_initiated_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816040a0)
Location: drivers/usb/core/hub.c:3796
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff816040a0-ffffffff816041f6: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81663d90)
Location: drivers/usb/core/hub.c:3797
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81663d90-ffffffff81663ee3: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691b90)
Location: drivers/usb/core/hub.c:3723
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81691b90-ffffffff81691ce3: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a7090)
Location: drivers/usb/core/hub.c:3742
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff816a7090-ffffffff816a71a6: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712460)
Location: drivers/usb/core/hub.c:3745
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81712460-ffffffff81712576: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817511b0)
Location: drivers/usb/core/hub.c:3796
Inline: False
```
**Symbols:**

```
ffffffff817511b0-ffffffff817512ca: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81775610)
Location: drivers/usb/core/hub.c:3858
Inline: False
```
**Symbols:**

```
ffffffff81775610-ffffffff8177572a: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3901
Inline: False
```
**Symbols:**

```
ffffffff817b3730-ffffffff817b382f: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff817ba107-ffffffff817ba17d: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
ffffffff817e3e60-ffffffff817e3f5f: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff817ea957-ffffffff817ea9cd: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3963
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff818b2860-ffffffff818b2938: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff818b9df0-ffffffff818b9e33: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff818c11d0-ffffffff818c12a8: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff81c1a916-ffffffff81c1a959: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4057
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff818a44b0-ffffffff818a4588: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff81c0c75c-ffffffff81c0c79f: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4061
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81939140-ffffffff8193923f: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff81d136cf-ffffffff81d1373c: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a90b50)
Location: drivers/usb/core/hub.c:4067
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81a90b50-ffffffff81a90cc9: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c12b30)
Location: drivers/usb/core/hub.c:4066
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81c12b30-ffffffff81c12ca9: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c799b0)
Location: drivers/usb/core/hub.c:4086
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81c799b0-ffffffff81c79b29: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2e3b0)
Location: drivers/usb/core/hub.c:4088
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81d2e3b0-ffffffff81d2e529: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a12388)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
ffff800010a12388-ffff800010a124d4: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeab5c)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
c0aeab5c-c0aeaca8: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac9c70)
Location: drivers/usb/core/hub.c:3949
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_link_state
```
**Symbols:**

```
c000000000ac9c70-c000000000ac9e70: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000638072)
Location: drivers/usb/core/hub.c:3949
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_link_state
```
**Symbols:**

```
ffffffe000638072-ffffffe000638194: usb_set_device_initiated_lpm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
ffffffff8179c240-ffffffff8179c33f: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff817a2d37-ffffffff817a2dad: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
ffffffff8178ded0-ffffffff8178dfcf: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff81794b77-ffffffff81794bed: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
ffffffff817d8ce0-ffffffff817d8ddf: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff817df7d7-ffffffff817df84d: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_set_device_initiated_lpm(struct usb_device *udev, enum usb3_link_state state, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3949
Inline: False
```
**Symbols:**

```
ffffffff817f3050-ffffffff817f314f: usb_set_device_initiated_lpm (STB_LOCAL)
ffffffff817f9ac7-ffffffff817f9b3d: usb_set_device_initiated_lpm.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
