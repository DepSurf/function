# Function: <code>xhci_get_timeout_no_hub_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164aa90)
Location: drivers/usb/host/xhci.c:4291
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff8164aa90-ffffffff8164abbd: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ab500)
Location: drivers/usb/host/xhci.c:4273
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816ab500-ffffffff816ab61e: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816d9620)
Location: drivers/usb/host/xhci.c:4266
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff816d9620-ffffffff816d973e: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ed920)
Location: drivers/usb/host/xhci.c:4216
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
```
**Symbols:**

```
ffffffff816ed920-ffffffff816eda3a: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175a110)
Location: drivers/usb/host/xhci.c:4222
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
```
**Symbols:**

```
ffffffff8175a110-ffffffff8175a22a: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179a7a0)
Location: drivers/usb/host/xhci.c:4407
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_update_timeout_for_endpoint
```
**Symbols:**

```
ffffffff8179a7a0-ffffffff8179a8b3: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c0b20)
Location: drivers/usb/host/xhci.c:4423
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817c0b20-ffffffff817c0c33: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4468
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81800510-ffffffff81800605: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff8180799f-ffffffff818079c0: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff818315b0-ffffffff818316a5: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff818388a7-ffffffff818388c8: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4549
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff81903930-ffffffff81903a25: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff8190b015-ffffffff8190b036: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4687
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff8190bea0-ffffffff8190bf95: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff81c20a42-ffffffff81c20a63: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4614
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff818ef590-ffffffff818ef6a1: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff81c12ac8-ffffffff81c12aea: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4635
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff8198c150-ffffffff8198c25b: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff81d1f747-ffffffff81d1f769: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4662
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff81ae8360-ffffffff81ae846b: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff81eeb237-ffffffff81eeb256: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c74380)
Location: drivers/usb/host/xhci.c:4666
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff81c74380-ffffffff81c744ad: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdb480)
Location: drivers/usb/host/xhci.c:4507
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff81cdb480-ffffffff81cdb5ac: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d904a0)
Location: drivers/usb/host/xhci.c:4567
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffff81d904a0-ffffffff81d905cc: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
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
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6dce0)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffff800010a6dce0-ffff800010a6de28: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b42178)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
c0b42178-c0b422e0: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b41d20)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
c000000000b41d20-c000000000b41e9c: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000686f24)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u2_timeout
  - drivers/usb/host/xhci.c:xhci_calculate_u1_timeout
```
**Symbols:**

```
ffffffe000686f24-ffffffe000687044: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
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
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817e9990-ffffffff817e9a85: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff817f0c57-ffffffff817f0c78: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff817aeaa0-ffffffff817aeb95: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff817b5ded-ffffffff817b5e0e: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81826430-ffffffff81826525: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff8182d727-ffffffff8182d748: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u16 xhci_get_timeout_no_hub_lpm(struct usb_device *udev, enum usb3_link_state state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4539
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout
```
**Symbols:**

```
ffffffff81840310-ffffffff81840405: xhci_get_timeout_no_hub_lpm (STB_LOCAL)
ffffffff81847810-ffffffff81847831: xhci_get_timeout_no_hub_lpm.cold (STB_LOCAL)
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
