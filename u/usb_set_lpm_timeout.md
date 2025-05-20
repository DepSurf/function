# Function: <code>usb_set_lpm_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81603f80)
Location: drivers/usb/core/hub.c:3851
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81603f80-ffffffff81604093: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81663c80)
Location: drivers/usb/core/hub.c:3852
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81663c80-ffffffff81663d8b: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691a80)
Location: drivers/usb/core/hub.c:3778
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81691a80-ffffffff81691b8b: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a6fa0)
Location: drivers/usb/core/hub.c:3797
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff816a6fa0-ffffffff816a708f: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712370)
Location: drivers/usb/core/hub.c:3800
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81712370-ffffffff8171245f: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817510b0)
Location: drivers/usb/core/hub.c:3851
Inline: False
```
**Symbols:**

```
ffffffff817510b0-ffffffff817511a5: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81775510)
Location: drivers/usb/core/hub.c:3913
Inline: False
```
**Symbols:**

```
ffffffff81775510-ffffffff81775605: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:3956
Inline: False
```
**Symbols:**

```
ffffffff817b3660-ffffffff817b372b: usb_set_lpm_timeout (STB_LOCAL)
ffffffff817ba092-ffffffff817ba107: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
ffffffff817e3d90-ffffffff817e3e5b: usb_set_lpm_timeout (STB_LOCAL)
ffffffff817ea8e2-ffffffff817ea957: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4018
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff818b3ea0-ffffffff818b3fe5: usb_set_lpm_timeout (STB_LOCAL)
ffffffff818b9f02-ffffffff818b9f53: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4036
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff818c2810-ffffffff818c2955: usb_set_lpm_timeout (STB_LOCAL)
ffffffff81c1aa28-ffffffff81c1aa79: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4112
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff818a5740-ffffffff818a5885: usb_set_lpm_timeout (STB_LOCAL)
ffffffff81c0c86e-ffffffff81c0c8bf: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4116
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff8193a490-ffffffff8193a5fa: usb_set_lpm_timeout (STB_LOCAL)
ffffffff81d1383c-ffffffff81d13862: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4122
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81a920e0-ffffffff81a9222f: usb_set_lpm_timeout (STB_LOCAL)
ffffffff81ede5e0-ffffffff81ede606: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c14260)
Location: drivers/usb/core/hub.c:4121
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81c14260-ffffffff81c143c6: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7b070)
Location: drivers/usb/core/hub.c:4141
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81c7b070-ffffffff81c7b1d6: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2fca0)
Location: drivers/usb/core/hub.c:4143
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_link_state
```
**Symbols:**

```
ffffffff81d2fca0-ffffffff81d2fe06: usb_set_lpm_timeout (STB_LOCAL)
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
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a12278)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
ffff800010a12278-ffff800010a12384: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeaa4c)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
c0aeaa4c-c0aeab5c: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac9af0)
Location: drivers/usb/core/hub.c:4004
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_link_state
  - drivers/usb/core/hub.c:usb_enable_link_state
```
**Symbols:**

```
c000000000ac9af0-c000000000ac9c64: usb_set_lpm_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000637f7e)
Location: drivers/usb/core/hub.c:4004
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_link_state
  - drivers/usb/core/hub.c:usb_enable_link_state
```
**Symbols:**

```
ffffffe000637f7e-ffffffe000638072: usb_set_lpm_timeout (STB_LOCAL)
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
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
ffffffff8179c170-ffffffff8179c23b: usb_set_lpm_timeout (STB_LOCAL)
ffffffff817a2cc2-ffffffff817a2d37: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
ffffffff8178de00-ffffffff8178decb: usb_set_lpm_timeout (STB_LOCAL)
ffffffff81794b02-ffffffff81794b77: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
ffffffff817d8c10-ffffffff817d8cdb: usb_set_lpm_timeout (STB_LOCAL)
ffffffff817df762-ffffffff817df7d7: usb_set_lpm_timeout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_set_lpm_timeout(struct usb_device *udev, enum usb3_link_state state, int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4004
Inline: False
```
**Symbols:**

```
ffffffff817f2f80-ffffffff817f304b: usb_set_lpm_timeout (STB_LOCAL)
ffffffff817f9a52-ffffffff817f9ac7: usb_set_lpm_timeout.cold (STB_LOCAL)
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
