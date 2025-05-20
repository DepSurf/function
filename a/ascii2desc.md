# Function: <code>ascii2desc</code>

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
In drivers/usb/core/hcd.c (ffffffff8160f182)
Location: drivers/usb/core/hcd.c:411
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8166ed80)
Location: drivers/usb/core/hcd.c:410
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8169ca60)
Location: drivers/usb/core/hcd.c:411
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff816b1e30)
Location: drivers/usb/core/hcd.c:412
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8171d46b)
Location: drivers/usb/core/hcd.c:399
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff8175bf1e)
Location: drivers/usb/core/hcd.c:399
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817804aa)
Location: drivers/usb/core/hcd.c:399
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
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
In drivers/usb/core/hcd.c (ffffffff817bdcba)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff817ee61a)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ascii2desc(const char *s, u8 *buf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bbd30)
Location: drivers/usb/core/hcd.c:403
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
**Symbols:**

```
ffffffff818bbd30-ffffffff818bbdb1: ascii2desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ascii2desc(const char *s, u8 *buf, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818c8af0)
Location: drivers/usb/core/hcd.c:403
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
**Symbols:**

```
ffffffff818c8af0-ffffffff818c8b71: ascii2desc (STB_LOCAL)
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
In drivers/usb/core/hcd.c (ffffffff818add25)
Location: drivers/usb/core/hcd.c:403
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff81942def)
Location: drivers/usb/core/hcd.c:403
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff81a996e8)
Location: drivers/usb/core/hcd.c:403
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_string
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1db38)
Location: drivers/usb/core/hcd.c:403
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_string
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c849f4)
Location: drivers/usb/core/hcd.c:403
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_string
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d393f4)
Location: drivers/usb/core/hcd.c:382
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_string
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
In drivers/usb/core/hcd.c (ffff800010a1d560)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (c0af4988)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (c000000000ad79a8)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffe000641d74)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff817a69fa)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff81797e1e)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff817e349a)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff817fcec4)
Location: drivers/usb/core/hcd.c:402
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
</ul>
