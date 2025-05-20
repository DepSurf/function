# Function: <code>usb_match_one_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81614a40)
Location: drivers/usb/core/driver.c:673
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_id
```
**Symbols:**

```
ffffffff81614a40-ffffffff81614a8a: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816749f0)
Location: drivers/usb/core/driver.c:683
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_id
```
**Symbols:**

```
ffffffff816749f0-ffffffff81674a3a: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a2680)
Location: drivers/usb/core/driver.c:686
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_id
```
**Symbols:**

```
ffffffff816a2680-ffffffff816a26ca: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b77e0)
Location: drivers/usb/core/driver.c:686
Inline: False
```
**Symbols:**

```
ffffffff816b77e0-ffffffff816b782b: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817230a0)
Location: drivers/usb/core/driver.c:686
Inline: False
```
**Symbols:**

```
ffffffff817230a0-ffffffff817230eb: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81761d50)
Location: drivers/usb/core/driver.c:686
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81761d50-ffffffff81761d9a: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81786360)
Location: drivers/usb/core/driver.c:683
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81786360-ffffffff817863aa: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c4951)
Location: drivers/usb/core/driver.c:678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff817c4810-ffffffff817c4853: usb_match_one_id.part.0 (STB_LOCAL)
ffffffff817c4860-ffffffff817c4878: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817f52f1)
Location: drivers/usb/core/driver.c:678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff817f51b0-ffffffff817f51f3: usb_match_one_id.part.0 (STB_LOCAL)
ffffffff817f5200-ffffffff817f5218: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818c53e3)
Location: drivers/usb/core/driver.c:713
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff818c5290-ffffffff818c52d9: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818d1213)
Location: drivers/usb/core/driver.c:713
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff818d10c0-ffffffff818d1109: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818b4833)
Location: drivers/usb/core/driver.c:709
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff818b46e0-ffffffff818b4729: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81949d63)
Location: drivers/usb/core/driver.c:709
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81949c10-ffffffff81949c59: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81aa290f)
Location: drivers/usb/core/driver.c:709
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81aa2860-ffffffff81aa28be: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c2834f)
Location: drivers/usb/core/driver.c:709
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81c28290-ffffffff81c282ee: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8f31f)
Location: drivers/usb/core/driver.c:709
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81c8f250-ffffffff81c8f2b1: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d43e9f)
Location: drivers/usb/core/driver.c:712
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_id
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81d43dd0-ffffffff81d43e31: usb_match_one_id (STB_GLOBAL)
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
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a25fd0)
Location: drivers/usb/core/driver.c:678
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffff800010a25fd0-ffff800010a2604c: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afc184)
Location: drivers/usb/core/driver.c:678
Inline: False
```
**Symbols:**

```
c0afc184-c0afc1d8: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae13e0)
Location: drivers/usb/core/driver.c:678
Inline: True
```
**Symbols:**

```
c000000000ae13e0-c000000000ae1478: usb_match_one_id.part.0 (STB_LOCAL)
c000000000ae1480-c000000000ae14a8: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe000647f7a)
Location: drivers/usb/core/driver.c:678
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffe000647f7a-ffffffe000647fdc: usb_match_one_id (STB_GLOBAL)
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
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ad6d1)
Location: drivers/usb/core/driver.c:678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff817ad590-ffffffff817ad5d3: usb_match_one_id.part.0 (STB_LOCAL)
ffffffff817ad5e0-ffffffff817ad5f8: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff8179f0d1)
Location: drivers/usb/core/driver.c:678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff8179ef90-ffffffff8179efd3: usb_match_one_id.part.0 (STB_LOCAL)
ffffffff8179efe0-ffffffff8179eff8: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817ea171)
Location: drivers/usb/core/driver.c:678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff817ea030-ffffffff817ea073: usb_match_one_id.part.0 (STB_LOCAL)
ffffffff817ea080-ffffffff817ea098: usb_match_one_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_match_one_id(struct usb_interface *interface, const struct usb_device_id *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff818043c1)
Location: drivers/usb/core/driver.c:678
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
Direct callers:
  - drivers/usb/core/driver.c:usb_match_dynamic_id
```
**Symbols:**

```
ffffffff81804280-ffffffff818042c3: usb_match_one_id.part.0 (STB_LOCAL)
ffffffff818042d0-ffffffff818042e8: usb_match_one_id (STB_GLOBAL)
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
