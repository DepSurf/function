# Function: <code>usb_parse_ssp_isoc_endpoint_companion</code>

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
In drivers/usb/core/config.c (ffffffff816167d6)
Location: drivers/usb/core/config.c:46
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
In drivers/usb/core/config.c (ffffffff816768a7)
Location: drivers/usb/core/config.c:46
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
In drivers/usb/core/config.c (ffffffff816a45b2)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff816b985d)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff81725170)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff8176408f)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff81788726)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff817c5d22)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff817f67d2)
Location: drivers/usb/core/config.c:51
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_endpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff818c62d2)
Location: drivers/usb/core/config.c:51
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff818d1f12)
Location: drivers/usb/core/config.c:51
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff818b5422)
Location: drivers/usb/core/config.c:51
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff8194a9a2)
Location: drivers/usb/core/config.c:51
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81aa36f0)
Location: drivers/usb/core/config.c:51
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_parse_ssp_isoc_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c291a0)
Location: drivers/usb/core/config.c:51
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
**Symbols:**

```
ffffffff81c291a0-ffffffff81c29201: usb_parse_ssp_isoc_endpoint_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_parse_ssp_isoc_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c90170)
Location: drivers/usb/core/config.c:51
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
**Symbols:**

```
ffffffff81c90170-ffffffff81c901d1: usb_parse_ssp_isoc_endpoint_companion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_parse_ssp_isoc_endpoint_companion(struct device *ddev, int cfgno, int inum, int asnum, struct usb_host_endpoint *ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d44d20)
Location: drivers/usb/core/config.c:51
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_ss_endpoint_companion
```
**Symbols:**

```
ffffffff81d44d20-ffffffff81d44d81: usb_parse_ssp_isoc_endpoint_companion (STB_LOCAL)
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
In drivers/usb/core/config.c (ffff800010a27878)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (c0afd818)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (c000000000ae34cc)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffe0006494c6)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff817aebb2)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff817a05b2)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff817eb652)
Location: drivers/usb/core/config.c:51
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
In drivers/usb/core/config.c (ffffffff81805892)
Location: drivers/usb/core/config.c:51
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
