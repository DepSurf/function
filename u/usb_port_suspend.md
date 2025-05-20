# Function: <code>usb_port_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81608b40)
Location: drivers/usb/core/hub.c:3174
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff81608b40-ffffffff81609010: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816687f0)
Location: drivers/usb/core/hub.c:3171
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff816687f0-ffffffff81668c61: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81696510)
Location: drivers/usb/core/hub.c:3097
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff81696510-ffffffff81696981: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ab920)
Location: drivers/usb/core/hub.c:3125
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff816ab920-ffffffff816abcf4: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81716d80)
Location: drivers/usb/core/hub.c:3128
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff81716d80-ffffffff81717154: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81755bb0)
Location: drivers/usb/core/hub.c:3172
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff81755bb0-ffffffff81755fa8: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177a0d0)
Location: drivers/usb/core/hub.c:3195
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff8177a0d0-ffffffff8177a49d: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3236
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff817baa4d-ffffffff817baacc: usb_port_suspend.cold (STB_LOCAL)
ffffffff817b7c60-ffffffff817b7fdd: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff817eb2c7-ffffffff817eb346: usb_port_suspend.cold (STB_LOCAL)
ffffffff817e8430-ffffffff817e87ad: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3294
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff818ba8e1-ffffffff818ba960: usb_port_suspend.cold (STB_LOCAL)
ffffffff818b7950-ffffffff818b7cfd: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3312
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81c1b407-ffffffff81c1b486: usb_port_suspend.cold (STB_LOCAL)
ffffffff818c6260-ffffffff818c660d: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3367
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81c0d2e8-ffffffff81c0d367: usb_port_suspend.cold (STB_LOCAL)
ffffffff818a9590-ffffffff818a99f9: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3371
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81d142e2-ffffffff81d14361: usb_port_suspend.cold (STB_LOCAL)
ffffffff8193e4a0-ffffffff8193e909: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3377
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81edee35-ffffffff81edeeb0: usb_port_suspend.cold (STB_LOCAL)
ffffffff81a964d0-ffffffff81a96935: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c19000)
Location: drivers/usb/core/hub.c:3396
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81c19000-ffffffff81c194df: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c80010)
Location: drivers/usb/core/hub.c:3416
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81c80010-ffffffff81c804fb: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d349e0)
Location: drivers/usb/core/hub.c:3418
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:usb_generic_driver_suspend
```
**Symbols:**

```
ffffffff81d349e0-ffffffff81d34ecb: usb_port_suspend (STB_GLOBAL)
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
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a17a48)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffff800010a17a48-ffff800010a17e10: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aefa78)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
c0aefa78-c0aefe90: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad0850)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
c000000000ad0850-c000000000ad0cdc: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063c80e)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffe00063c80e-ffffffe00063cbce: usb_port_suspend (STB_GLOBAL)
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
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff817a36a7-ffffffff817a3726: usb_port_suspend.cold (STB_LOCAL)
ffffffff817a0810-ffffffff817a0b8d: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff81795218-ffffffff81795297: usb_port_suspend.cold (STB_LOCAL)
ffffffff81792650-ffffffff817929cd: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff817e0147-ffffffff817e01c6: usb_port_suspend.cold (STB_LOCAL)
ffffffff817dd2b0-ffffffff817dd62d: usb_port_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_port_suspend(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3280
Inline: False
Direct callers:
  - drivers/usb/core/generic.c:generic_suspend
```
**Symbols:**

```
ffffffff817fa437-ffffffff817fa4b6: usb_port_suspend.cold (STB_LOCAL)
ffffffff817f7580-ffffffff817f78fd: usb_port_suspend (STB_GLOBAL)
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
