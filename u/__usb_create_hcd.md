# Function: <code>__usb_create_hcd</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816b0720)
Location: drivers/usb/core/hcd.c:2514
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff816b0720-ffffffff816b09b3: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171bd30)
Location: drivers/usb/core/hcd.c:2503
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff8171bd30-ffffffff8171bfb9: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8175aa80)
Location: drivers/usb/core/hcd.c:2519
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff8175aa80-ffffffff8175ad07: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8177efb0)
Location: drivers/usb/core/hcd.c:2503
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff8177efb0-ffffffff8177f237: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bc120)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff817bc120-ffffffff817bc3e9: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817ec950)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff817ec950-ffffffff817ecc0b: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bc440)
Location: drivers/usb/core/hcd.c:2409
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff818bc440-ffffffff818bc700: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c91a0)
Location: drivers/usb/core/hcd.c:2419
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff818c91a0-ffffffff818c9460: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ac700)
Location: drivers/usb/core/hcd.c:2419
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff818ac700-ffffffff818ac9c0: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81941750)
Location: drivers/usb/core/hcd.c:2570
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff81941750-ffffffff81941a0a: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a9a150)
Location: drivers/usb/core/hcd.c:2573
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff81a9a150-ffffffff81a9a3f3: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1e6d0)
Location: drivers/usb/core/hcd.c:2567
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff81c1e6d0-ffffffff81c1e978: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c855d0)
Location: drivers/usb/core/hcd.c:2571
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff81c855d0-ffffffff81c85878: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3a210)
Location: drivers/usb/core/hcd.c:2546
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff81d3a210-ffffffff81d3a543: __usb_create_hcd (STB_GLOBAL)
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
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1bc20)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffff800010a1bc20-ffff800010a1be70: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af4bf0)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
c0af4bf0-c0af4e50: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad54f0)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
c000000000ad54f0-c000000000ad57c4: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe0006403ae)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffe0006403ae-ffffffe0006405fc: __usb_create_hcd (STB_GLOBAL)
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
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a4d30)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff817a4d30-ffffffff817a4feb: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81796840)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff81796840-ffffffff81796afb: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e17d0)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff817e17d0-ffffffff817e1a8b: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct usb_hcd *__usb_create_hcd(const struct hc_driver *driver, struct device *sysdev, struct device *dev, const char *bus_name, struct usb_hcd *primary_hcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fbbc0)
Location: drivers/usb/core/hcd.c:2412
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_create_hcd
  - drivers/usb/core/hcd.c:usb_create_shared_hcd
```
**Symbols:**

```
ffffffff817fbbc0-ffffffff817fbe7b: __usb_create_hcd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
