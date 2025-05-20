# Function: <code>cdc_parse_cdc_header</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816715e0)
Location: drivers/usb/core/message.c:2043
Inline: False
```
**Symbols:**

```
ffffffff816715e0-ffffffff8167193e: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8169f290)
Location: drivers/usb/core/message.c:2048
Inline: False
```
**Symbols:**

```
ffffffff8169f290-ffffffff8169f5ee: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff816b44a0)
Location: drivers/usb/core/message.c:2046
Inline: False
```
**Symbols:**

```
ffffffff816b44a0-ffffffff816b4810: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81720280)
Location: drivers/usb/core/message.c:2085
Inline: True
```
**Symbols:**

```
ffffffff81720280-ffffffff8172064e: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff8175eb30)
Location: drivers/usb/core/message.c:2128
Inline: True
```
**Symbols:**

```
ffffffff8175eb30-ffffffff8175ef0c: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff817832b0)
Location: drivers/usb/core/message.c:2128
Inline: True
```
**Symbols:**

```
ffffffff817832b0-ffffffff8178368c: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffff817c3496-ffffffff817c3595: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff817c11e0-ffffffff817c151a: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffff817f3e16-ffffffff817f3f15: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff817f1b60-ffffffff817f1e9a: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2139
Inline: False
```
**Symbols:**

```
ffffffff818c3997-ffffffff818c3a96: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff818c14e0-ffffffff818c1815: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2278
Inline: False
```
**Symbols:**

```
ffffffff81c1cf54-ffffffff81c1d053: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff818cd790-ffffffff818cdae1: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2284
Inline: False
```
**Symbols:**

```
ffffffff81c0ee1a-ffffffff81c0ef19: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff818b0dd0-ffffffff818b1121: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2284
Inline: False
```
**Symbols:**

```
ffffffff81d15fba-ffffffff81d160b9: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff81946030-ffffffff81946381: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2284
Inline: False
```
**Symbols:**

```
ffffffff81ee0b65-ffffffff81ee0c70: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff81a9e7d0-ffffffff81a9eb39: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c238d0)
Location: drivers/usb/core/message.c:2285
Inline: False
```
**Symbols:**

```
ffffffff81c238d0-ffffffff81c23cd2: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81c8a850)
Location: drivers/usb/core/message.c:2320
Inline: False
```
**Symbols:**

```
ffffffff81c8a850-ffffffff81c8ac42: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffff81d3f270)
Location: drivers/usb/core/message.c:2321
Inline: False
```
**Symbols:**

```
ffffffff81d3f270-ffffffff81d3f662: cdc_parse_cdc_header (STB_GLOBAL)
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
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffff800010a21e80)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffff800010a21e80-ffff800010a22204: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c0af8c68)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
c0af8c68-c0af8fb8: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (c000000000adc740)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
c000000000adc740-c000000000adcbc4: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/message.c (ffffffe000644b84)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffe000644b84-ffffffe000644f12: cdc_parse_cdc_header (STB_GLOBAL)
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
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffff817ac1f6-ffffffff817ac2f5: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff817a9f40-ffffffff817aa27a: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffff8179dbf6-ffffffff8179dcf5: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff8179b940-ffffffff8179bc7a: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffff817e8c96-ffffffff817e8d95: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff817e69e0-ffffffff817e6d1a: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cdc_parse_cdc_header(struct usb_cdc_parsed_header *hdr, struct usb_interface *intf, u8 *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/message.c (0)
Location: drivers/usb/core/message.c:2137
Inline: False
```
**Symbols:**

```
ffffffff81802ee6-ffffffff81802fe5: cdc_parse_cdc_header.cold (STB_LOCAL)
ffffffff81800da0-ffffffff818010da: cdc_parse_cdc_header (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
