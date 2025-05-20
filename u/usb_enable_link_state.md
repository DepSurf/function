# Function: <code>usb_enable_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604c90)
Location: drivers/usb/core/hub.c:3906
Inline: True
```
**Symbols:**

```
ffffffff81604c90-ffffffff81604f76: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816649c0)
Location: drivers/usb/core/hub.c:3907
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff816649c0-ffffffff81664cb7: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816924e0)
Location: drivers/usb/core/hub.c:3833
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff816924e0-ffffffff816927d7: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a7e30)
Location: drivers/usb/core/hub.c:3852
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff816a7e30-ffffffff816a8105: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81713000)
Location: drivers/usb/core/hub.c:3855
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81713000-ffffffff817132e1: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81751ea0)
Location: drivers/usb/core/hub.c:3906
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81751ea0-ffffffff8175215c: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776320)
Location: drivers/usb/core/hub.c:3968
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81776320-ffffffff817765dc: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b41b2)
Location: drivers/usb/core/hub.c:4014
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff817b4160-ffffffff817b443d: usb_enable_link_state (STB_LOCAL)
ffffffff817ba27d-ffffffff817ba2af: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e48e2)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff817e4890-ffffffff817e4b6d: usb_enable_link_state (STB_LOCAL)
ffffffff817eaacd-ffffffff817eaaff: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b4266)
Location: drivers/usb/core/hub.c:4076
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff818b4090-ffffffff818b4188: usb_enable_link_state.part.0 (STB_LOCAL)
ffffffff818b9f76-ffffffff818b9fbd: usb_enable_link_state.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c2bd6)
Location: drivers/usb/core/hub.c:4094
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff818c2a00-ffffffff818c2af8: usb_enable_link_state.part.0 (STB_LOCAL)
ffffffff81c1aa9c-ffffffff81c1aae3: usb_enable_link_state.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a5bc6)
Location: drivers/usb/core/hub.c:4211
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff818a5930-ffffffff818a5ae7: usb_enable_link_state.part.0 (STB_LOCAL)
ffffffff81c0c8e2-ffffffff81c0c929: usb_enable_link_state.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193aa26)
Location: drivers/usb/core/hub.c:4215
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff8193a6d0-ffffffff8193a941: usb_enable_link_state.part.0 (STB_LOCAL)
ffffffff81d13862-ffffffff81d13897: usb_enable_link_state.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a926a8)
Location: drivers/usb/core/hub.c:4221
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81a92310-ffffffff81a925cb: usb_enable_link_state.part.0 (STB_LOCAL)
ffffffff81ede606-ffffffff81ede63b: usb_enable_link_state.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1453b)
Location: drivers/usb/core/hub.c:4223
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81c144d0-ffffffff81c14731: usb_enable_link_state (STB_LOCAL)
ffffffff8209e72c-ffffffff8209e761: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7b345)
Location: drivers/usb/core/hub.c:4243
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81c7b2e0-ffffffff81c7b537: usb_enable_link_state (STB_LOCAL)
ffffffff8211fcb3-ffffffff8211fccc: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2ff81)
Location: drivers/usb/core/hub.c:4245
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff81d2ff10-ffffffff81d3018c: usb_enable_link_state (STB_LOCAL)
ffffffff82201499-ffffffff822014b2: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a13198)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffff800010a13198-ffff800010a13468: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeb954)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
c0aeb954-c0aebcc4: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac9e70)
Location: drivers/usb/core/hub.c:4062
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
c000000000ac9e70-c000000000aca2c4: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000638194)
Location: drivers/usb/core/hub.c:4062
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffe000638194-ffffffe000638436: usb_enable_link_state (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179ccc2)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff8179cc70-ffffffff8179cf4d: usb_enable_link_state (STB_LOCAL)
ffffffff817a2ead-ffffffff817a2edf: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178e952)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff8178e900-ffffffff8178ebdd: usb_enable_link_state (STB_LOCAL)
ffffffff81794ced-ffffffff81794d1f: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d9762)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff817d9710-ffffffff817d99ed: usb_enable_link_state (STB_LOCAL)
ffffffff817df94d-ffffffff817df97f: usb_enable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void usb_enable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f3ad2)
Location: drivers/usb/core/hub.c:4062
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_enable_lpm
  - drivers/usb/core/hub.c:usb_enable_lpm
```
**Symbols:**

```
ffffffff817f3a80-ffffffff817f3d5d: usb_enable_link_state (STB_LOCAL)
ffffffff817f9c3d-ffffffff817f9c6f: usb_enable_link_state.cold (STB_LOCAL)
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
