# Function: <code>usb_parse_ss_endpoint_companion</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81616255)
Location: drivers/usb/core/config.c:67
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81675f97)
Location: drivers/usb/core/config.c:67
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816a3c38)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816b8d04)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81724615)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff8176377e)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81787dd7)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817c5a65)
Location: drivers/usb/core/config.c:72
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817f6670)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818c61e0-ffffffff818c6361: usb_parse_ss_endpoint_companion (STB_LOCAL)
ffffffff818c778e-ffffffff818c7a00: usb_parse_ss_endpoint_companion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818d1e20-ffffffff818d1fa1: usb_parse_ss_endpoint_companion (STB_LOCAL)
ffffffff81c1d4e4-ffffffff81c1d756: usb_parse_ss_endpoint_companion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff818b5330-ffffffff818b54af: usb_parse_ss_endpoint_companion (STB_LOCAL)
ffffffff81c0f3a7-ffffffff81c0f618: usb_parse_ss_endpoint_companion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff8194a8b0-ffffffff8194aa2f: usb_parse_ss_endpoint_companion (STB_LOCAL)
ffffffff81d16548-ffffffff81d167b9: usb_parse_ss_endpoint_companion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81aa35e0-ffffffff81aa377c: usb_parse_ss_endpoint_companion (STB_LOCAL)
ffffffff81ee1124-ffffffff81ee13a0: usb_parse_ss_endpoint_companion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c29220)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81c29220-ffffffff81c29598: usb_parse_ss_endpoint_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c901f0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81c901f0-ffffffff81c90568: usb_parse_ss_endpoint_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_parse_ss_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d44da0)
Location: drivers/usb/core/config.c:72
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
**Symbols:**

```
ffffffff81d44da0-ffffffff81d45118: usb_parse_ss_endpoint_companion (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffff800010a276f0)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c0afd440)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c000000000ae2f64)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffe0006490e6)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817aea50)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817a0450)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817eb4f0)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81805730)
Location: drivers/usb/core/config.c:72
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
