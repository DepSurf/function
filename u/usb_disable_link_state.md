# Function: <code>usb_disable_link_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604200)
Location: drivers/usb/core/hub.c:3991
Inline: False
```
**Symbols:**

```
ffffffff81604200-ffffffff816042d5: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81663ef0)
Location: drivers/usb/core/hub.c:3992
Inline: False
```
**Symbols:**

```
ffffffff81663ef0-ffffffff81663fc5: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691cf0)
Location: drivers/usb/core/hub.c:3918
Inline: False
```
**Symbols:**

```
ffffffff81691cf0-ffffffff81691dc5: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a71b0)
Location: drivers/usb/core/hub.c:3937
Inline: False
```
**Symbols:**

```
ffffffff816a71b0-ffffffff816a725c: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712580)
Location: drivers/usb/core/hub.c:3940
Inline: False
```
**Symbols:**

```
ffffffff81712580-ffffffff81712636: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81751df0)
Location: drivers/usb/core/hub.c:3991
Inline: True
```
**Symbols:**

```
ffffffff81751df0-ffffffff81751e9e: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776270)
Location: drivers/usb/core/hub.c:4053
Inline: True
```
**Symbols:**

```
ffffffff81776270-ffffffff8177631e: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817ba258)
Location: drivers/usb/core/hub.c:4100
Inline: True
```
**Symbols:**

```
ffffffff817b40c0-ffffffff817b415b: usb_disable_link_state (STB_LOCAL)
ffffffff817ba236-ffffffff817ba27d: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817eaaa8)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffffffff817e47f0-ffffffff817e488b: usb_disable_link_state (STB_LOCAL)
ffffffff817eaa86-ffffffff817eaacd: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4162
Inline: False
```
**Symbols:**

```
ffffffff818b3ff0-ffffffff818b4082: usb_disable_link_state (STB_LOCAL)
ffffffff818b9f53-ffffffff818b9f76: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4180
Inline: False
```
**Symbols:**

```
ffffffff818c2960-ffffffff818c29f2: usb_disable_link_state (STB_LOCAL)
ffffffff81c1aa79-ffffffff81c1aa9c: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4300
Inline: False
```
**Symbols:**

```
ffffffff818a5890-ffffffff818a5922: usb_disable_link_state (STB_LOCAL)
ffffffff81c0c8bf-ffffffff81c0c8e2: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193a600)
Location: drivers/usb/core/hub.c:4304
Inline: False
```
**Symbols:**

```
ffffffff8193a600-ffffffff8193a6c5: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a92230)
Location: drivers/usb/core/hub.c:4310
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/hub.c:usb_disable_lpm
```
**Symbols:**

```
ffffffff81a92230-ffffffff81a92309: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c143e0)
Location: drivers/usb/core/hub.c:4301
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/hub.c:usb_disable_lpm
```
**Symbols:**

```
ffffffff81c143e0-ffffffff81c144bd: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7b1f0)
Location: drivers/usb/core/hub.c:4321
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/hub.c:usb_disable_lpm
```
**Symbols:**

```
ffffffff81c7b1f0-ffffffff81c7b2cd: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2fe20)
Location: drivers/usb/core/hub.c:4330
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/hub.c:usb_disable_lpm
```
**Symbols:**

```
ffffffff81d2fe20-ffffffff81d2fefd: usb_disable_link_state (STB_LOCAL)
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
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a130c0)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffff800010a130c0-ffff800010a13194: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeb8a4)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
c0aeb8a4-c0aeb954: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acb5a0)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
c000000000acb5a0-c000000000acb700: usb_disable_link_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000638f6a)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffffffe000638f6a-ffffffe000639018: usb_disable_link_state (STB_LOCAL)
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
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a2e88)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffffffff8179cbd0-ffffffff8179cc6b: usb_disable_link_state (STB_LOCAL)
ffffffff817a2e66-ffffffff817a2ead: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81794cc8)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffffffff8178e860-ffffffff8178e8fb: usb_disable_link_state (STB_LOCAL)
ffffffff81794ca6-ffffffff81794ced: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817df928)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffffffff817d9670-ffffffff817d970b: usb_disable_link_state (STB_LOCAL)
ffffffff817df906-ffffffff817df94d: usb_disable_link_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_disable_link_state(struct usb_hcd *hcd, struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f9c18)
Location: drivers/usb/core/hub.c:4148
Inline: True
```
**Symbols:**

```
ffffffff817f39e0-ffffffff817f3a7b: usb_disable_link_state (STB_LOCAL)
ffffffff817f9bf6-ffffffff817f9c3d: usb_disable_link_state.cold (STB_LOCAL)
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
