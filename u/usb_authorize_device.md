# Function: <code>usb_authorize_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81608a40)
Location: drivers/usb/core/hub.c:2581
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81608a40-ffffffff81608b3d: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816686f0)
Location: drivers/usb/core/hub.c:2578
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff816686f0-ffffffff816687ed: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81696410)
Location: drivers/usb/core/hub.c:2497
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81696410-ffffffff8169650d: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ab820)
Location: drivers/usb/core/hub.c:2525
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff816ab820-ffffffff816ab918: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81716c80)
Location: drivers/usb/core/hub.c:2525
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81716c80-ffffffff81716d78: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81755ab0)
Location: drivers/usb/core/hub.c:2553
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81755ab0-ffffffff81755ba8: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81779fd0)
Location: drivers/usb/core/hub.c:2564
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81779fd0-ffffffff8177a0c8: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2604
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff817ba9f5-ffffffff817baa4d: usb_authorize_device.cold (STB_LOCAL)
ffffffff817b7ba0-ffffffff817b7c5a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff817eb26f-ffffffff817eb2c7: usb_authorize_device.cold (STB_LOCAL)
ffffffff817e8370-ffffffff817e842a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2622
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff818ba889-ffffffff818ba8e1: usb_authorize_device.cold (STB_LOCAL)
ffffffff818b7890-ffffffff818b794a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2623
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81c1b3af-ffffffff81c1b407: usb_authorize_device.cold (STB_LOCAL)
ffffffff818c61a0-ffffffff818c625a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2630
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81c0d290-ffffffff81c0d2e8: usb_authorize_device.cold (STB_LOCAL)
ffffffff818a94d0-ffffffff818a958a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2634
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81d1428a-ffffffff81d142e2: usb_authorize_device.cold (STB_LOCAL)
ffffffff8193e3e0-ffffffff8193e49a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2634
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81ededdc-ffffffff81edee35: usb_authorize_device.cold (STB_LOCAL)
ffffffff81a96400-ffffffff81a964c1: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c18e90)
Location: drivers/usb/core/hub.c:2643
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81c18e90-ffffffff81c18f94: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7fe70)
Location: drivers/usb/core/hub.c:2658
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81c7fe70-ffffffff81c7ffa6: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d348a0)
Location: drivers/usb/core/hub.c:2684
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff81d348a0-ffffffff81d34974: usb_authorize_device (STB_GLOBAL)
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
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a17928)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffff800010a17928-ffff800010a17a44: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aef96c)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
c0aef96c-c0aefa78: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad06c0)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
c000000000ad06c0-c000000000ad084c: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063c6fe)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffe00063c6fe-ffffffe00063c80e: usb_authorize_device (STB_GLOBAL)
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
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff817a364f-ffffffff817a36a7: usb_authorize_device.cold (STB_LOCAL)
ffffffff817a0750-ffffffff817a080a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff817951c0-ffffffff81795218: usb_authorize_device.cold (STB_LOCAL)
ffffffff81792590-ffffffff8179264a: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff817e00ef-ffffffff817e0147: usb_authorize_device.cold (STB_LOCAL)
ffffffff817dd1f0-ffffffff817dd2aa: usb_authorize_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_authorize_device(struct usb_device *usb_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:2615
Inline: False
Direct callers:
  - drivers/usb/core/sysfs.c:authorized_store
```
**Symbols:**

```
ffffffff817fa3df-ffffffff817fa437: usb_authorize_device.cold (STB_LOCAL)
ffffffff817f74c0-ffffffff817f757a: usb_authorize_device (STB_GLOBAL)
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
