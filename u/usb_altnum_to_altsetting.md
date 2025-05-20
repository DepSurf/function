# Function: <code>usb_altnum_to_altsetting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81602f80)
Location: drivers/usb/core/usb.c:175
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_configuration
```
**Symbols:**

```
ffffffff81602f80-ffffffff81602fc5: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81662c40)
Location: drivers/usb/core/usb.c:171
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81662c40-ffffffff81662c85: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81690a30)
Location: drivers/usb/core/usb.c:174
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81690a30-ffffffff81690a75: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff816a5f80)
Location: drivers/usb/core/usb.c:308
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff816a5f80-ffffffff816a5fc5: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81711350)
Location: drivers/usb/core/usb.c:308
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81711350-ffffffff81711395: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817500d0)
Location: drivers/usb/core/usb.c:310
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff817500d0-ffffffff81750115: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81774500)
Location: drivers/usb/core/usb.c:310
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81774500-ffffffff81774545: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817b2630)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff817b2630-ffffffff817b266f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817e2d60)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff817e2d60-ffffffff817e2d9f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818b18b0)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff818b18b0-ffffffff818b18ef: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818c0260)
Location: drivers/usb/core/usb.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff818c0260-ffffffff818c029f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff818a3450)
Location: drivers/usb/core/usb.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff818a3450-ffffffff818a348f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81938010)
Location: drivers/usb/core/usb.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81938010-ffffffff8193804f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81a8f7b0)
Location: drivers/usb/core/usb.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81a8f7b0-ffffffff81a8f80e: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c11480)
Location: drivers/usb/core/usb.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81c11480-ffffffff81c114de: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81c78240)
Location: drivers/usb/core/usb.c:383
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81c78240-ffffffff81c7829e: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff81d2cc40)
Location: drivers/usb/core/usb.c:384
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff81d2cc40-ffffffff81d2cc9e: usb_altnum_to_altsetting (STB_GLOBAL)
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
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffff800010a110c8)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffff800010a110c8-ffff800010a11134: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c0ae9798)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
c0ae9798-c0ae97e8: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (c000000000ac8060)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
c000000000ac8060-c000000000ac80b8: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffe000636cd2)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffe000636cd2-ffffffe000636d2e: usb_altnum_to_altsetting (STB_GLOBAL)
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
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8179b140)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff8179b140-ffffffff8179b17f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff8178cdd0)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff8178cdd0-ffffffff8178ce0f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817d7be0)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff817d7be0-ffffffff817d7c1f: usb_altnum_to_altsetting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct usb_host_interface *usb_altnum_to_altsetting(const struct usb_interface *intf, unsigned int altnum);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/usb.c (ffffffff817f1e80)
Location: drivers/usb/core/usb.c:309
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_alloc_bandwidth
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
```
**Symbols:**

```
ffffffff817f1e80-ffffffff817f1ebf: usb_altnum_to_altsetting (STB_GLOBAL)
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
