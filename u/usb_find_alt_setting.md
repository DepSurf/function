# Function: <code>usb_find_alt_setting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81603550)
Location: drivers/usb/core/usb.c:90
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81603550-ffffffff816035f9: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81663210)
Location: drivers/usb/core/usb.c:86
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81663210-ffffffff816632c0: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81691000)
Location: drivers/usb/core/usb.c:89
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81691000-ffffffff816910b0: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a6520)
Location: drivers/usb/core/usb.c:223
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
```
**Symbols:**

```
ffffffff816a6520-ffffffff816a65cc: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817118f0)
Location: drivers/usb/core/usb.c:223
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
```
**Symbols:**

```
ffffffff817118f0-ffffffff8171199c: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:223
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81750ae9-ffffffff81750b06: usb_find_alt_setting.cold.15 (STB_LOCAL)
ffffffff81750620-ffffffff817506c0: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81774f46)
Location: drivers/usb/core/usb.c:223
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81774f44-ffffffff81774f61: usb_find_alt_setting.cold.15 (STB_LOCAL)
ffffffff81774ad0-ffffffff81774b71: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817b306a)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817b306a-ffffffff817b3087: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff817b2be0-ffffffff817b2c6e: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817e379a)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817e379a-ffffffff817e37b7: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff817e3310-ffffffff817e339e: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff818b22e9-ffffffff818b2306: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff818b1e60-ffffffff818b1eee: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:220
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81c1a800-ffffffff81c1a81d: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff818c0850-ffffffff818c08de: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:220
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81c0c71b-ffffffff81c0c736: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff818a3ad0-ffffffff818a3b5b: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:220
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81d1364c-ffffffff81d1366a: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff819386b0-ffffffff819387b2: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (0)
Location: drivers/usb/core/usb.c:220
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81ede398-ffffffff81ede3b4: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff81a8f830-ffffffff81a8f93c: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c11520)
Location: drivers/usb/core/usb.c:220
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81c11520-ffffffff81c11658: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c782e0)
Location: drivers/usb/core/usb.c:296
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81c782e0-ffffffff81c78418: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2cce0)
Location: drivers/usb/core/usb.c:297
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff81d2cce0-ffffffff81d2ce18: usb_find_alt_setting (STB_GLOBAL)
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
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a11950)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffff800010a11950-ffff800010a11a38: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0aea120)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
c0aea120-c0aea1e0: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac8ad0)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
c000000000ac8ad0-c000000000ac8bd4: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe0006373ae)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffe0006373ae-ffffffe000637460: usb_find_alt_setting (STB_GLOBAL)
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
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8179bb7a)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff8179bb7a-ffffffff8179bb97: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff8179b6f0-ffffffff8179b77e: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8178d80a)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff8178d80a-ffffffff8178d827: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff8178d380-ffffffff8178d40e: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817d861a)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817d861a-ffffffff817d8637: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff817d8190-ffffffff817d821e: usb_find_alt_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_host_interface *usb_find_alt_setting(struct usb_host_config *config, unsigned int iface_num, unsigned int alt_num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817f28ba)
Location: drivers/usb/core/usb.c:222
Inline: True
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/devio.c:check_ctrlrecip
```
**Symbols:**

```
ffffffff817f28ba-ffffffff817f28d7: usb_find_alt_setting.cold (STB_LOCAL)
ffffffff817f2430-ffffffff817f24be: usb_find_alt_setting (STB_GLOBAL)
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
