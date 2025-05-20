# Function: <code>usb_phy_roothub_exit</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff8176d010)
Location: drivers/usb/core/phy.c:104
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff8176d010-ffffffff8176d068: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81791660)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff81791660-ffffffff817916b8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817cff10)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817cff10-ffffffff817cff68: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81800d90)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff81800d90-ffffffff81800de8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff818d172f)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818d1470-ffffffff818d14c8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff818dbb0f)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818db850-ffffffff818db8a8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff818beecf)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818bec10-ffffffff818bec68: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff8195552f)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81955270-ffffffff819552c8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81aaef1a)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81aaebb0-ffffffff81aaec14: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81c36a0a)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c36640-ffffffff81c366a4: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81c9dcfa)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c9d930-ffffffff81c9d994: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff81d528aa)
Location: drivers/usb/core/phy.c:105
Inline: True
Inline callers:
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81d524e0-ffffffff81d52544: usb_phy_roothub_exit (STB_GLOBAL)
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
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffff800010a34f30)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffff800010a34f30-ffff800010a34fb4: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (c0b0869c)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
c0b0869c-c0b086f8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (c000000000af29a0)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
c000000000af29a0-c000000000af2a6c: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffe000652798)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffe000652798-ffffffe0006527fa: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817b9170)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817b9170-ffffffff817b91c8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817aaba0)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817aaba0-ffffffff817aabf8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff817f5c10)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff817f5c10-ffffffff817f5c68: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_phy_roothub_exit(struct usb_phy_roothub *phy_roothub);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/phy.c (ffffffff8180fe50)
Location: drivers/usb/core/phy.c:105
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
  - drivers/usb/core/phy.c:usb_phy_roothub_resume
  - drivers/usb/core/phy.c:usb_phy_roothub_suspend
```
**Symbols:**

```
ffffffff8180fe50-ffffffff8180fea8: usb_phy_roothub_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
