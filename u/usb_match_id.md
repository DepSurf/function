# Function: <code>usb_match_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81614a90)
Location: drivers/usb/core/driver.c:766
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81614a90-ffffffff81614b00: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81674a40)
Location: drivers/usb/core/driver.c:776
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81674a40-ffffffff81674ab0: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a26d0)
Location: drivers/usb/core/driver.c:779
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff816a26d0-ffffffff816a2740: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b82d6)
Location: drivers/usb/core/driver.c:779
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff816b7830-ffffffff816b789b: usb_match_id.part.11 (STB_LOCAL)
ffffffff816b78a0-ffffffff816b78b8: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81723beb)
Location: drivers/usb/core/driver.c:779
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817230f0-ffffffff8172315b: usb_match_id.part.11 (STB_LOCAL)
ffffffff81723160-ffffffff81723178: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8176282b)
Location: drivers/usb/core/driver.c:779
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81761da0-ffffffff81761e0b: usb_match_id.part.14 (STB_LOCAL)
ffffffff81761e10-ffffffff81761e28: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81786e39)
Location: drivers/usb/core/driver.c:776
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817863b0-ffffffff8178641b: usb_match_id.part.14 (STB_LOCAL)
ffffffff81786420-ffffffff81786438: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c5318)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817c4880-ffffffff817c48f4: usb_match_id.part.0 (STB_LOCAL)
ffffffff817c4900-ffffffff817c4918: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817f5cb8)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817f5220-ffffffff817f5294: usb_match_id.part.0 (STB_LOCAL)
ffffffff817f52a0-ffffffff817f52b8: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c5492)
Location: drivers/usb/core/driver.c:806
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818c52e0-ffffffff818c537e: usb_match_id.part.0 (STB_LOCAL)
ffffffff818c5380-ffffffff818c5398: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d16be)
Location: drivers/usb/core/driver.c:806
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818d1110-ffffffff818d11ae: usb_match_id.part.0 (STB_LOCAL)
ffffffff818d11b0-ffffffff818d11c8: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b4cde)
Location: drivers/usb/core/driver.c:802
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818b4730-ffffffff818b47ce: usb_match_id.part.0 (STB_LOCAL)
ffffffff818b47d0-ffffffff818b47e8: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8194a20e)
Location: drivers/usb/core/driver.c:802
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81949c60-ffffffff81949cfe: usb_match_id.part.0 (STB_LOCAL)
ffffffff81949d00-ffffffff81949d18: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa28c0)
Location: drivers/usb/core/driver.c:802
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81aa28c0-ffffffff81aa2973: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c28300)
Location: drivers/usb/core/driver.c:802
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81c28300-ffffffff81c283b3: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8f2d0)
Location: drivers/usb/core/driver.c:802
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81c8f2d0-ffffffff81c8f386: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d43e50)
Location: drivers/usb/core/driver.c:805
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_device_match
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81d43e50-ffffffff81d43f06: usb_match_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a26c88)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffff800010a26050-ffff800010a260dc: usb_match_id.part.0 (STB_LOCAL)
ffff800010a260e0-ffff800010a26120: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (c0afcce4)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
c0afc1d8-c0afc25c: usb_match_id.part.0 (STB_LOCAL)
c0afc25c-c0afc288: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae2664)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
c000000000ae14b0-c000000000ae1564: usb_match_id.part.0 (STB_LOCAL)
c000000000ae1570-c000000000ae1598: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe000648aaa)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffe000647fdc-ffffffe000648048: usb_match_id.part.0 (STB_LOCAL)
ffffffe000648048-ffffffe000648080: usb_match_id (STB_GLOBAL)
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
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ae098)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817ad600-ffffffff817ad674: usb_match_id.part.0 (STB_LOCAL)
ffffffff817ad680-ffffffff817ad698: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8179fa98)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff8179f000-ffffffff8179f074: usb_match_id.part.0 (STB_LOCAL)
ffffffff8179f080-ffffffff8179f098: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817eab38)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817ea0a0-ffffffff817ea114: usb_match_id.part.0 (STB_LOCAL)
ffffffff817ea120-ffffffff817ea138: usb_match_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct usb_device_id *usb_match_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81804d78)
Location: drivers/usb/core/driver.c:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_probe_interface
Direct callers:
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818042f0-ffffffff81804364: usb_match_id.part.0 (STB_LOCAL)
ffffffff81804370-ffffffff81804388: usb_match_id (STB_GLOBAL)
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
