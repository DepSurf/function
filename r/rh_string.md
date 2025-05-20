# Function: <code>rh_string</code>

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
In drivers/usb/core/hcd.c (ffffffff8160f086)
Location: drivers/usb/core/hcd.c:447
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
In drivers/usb/core/hcd.c (ffffffff8166ec09)
Location: drivers/usb/core/hcd.c:446
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
In drivers/usb/core/hcd.c (ffffffff8169c8e9)
Location: drivers/usb/core/hcd.c:447
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
In drivers/usb/core/hcd.c (ffffffff816b1d2b)
Location: drivers/usb/core/hcd.c:448
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
In drivers/usb/core/hcd.c (ffffffff8171d366)
Location: drivers/usb/core/hcd.c:435
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
In drivers/usb/core/hcd.c (ffffffff8175bea1)
Location: drivers/usb/core/hcd.c:435
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
In drivers/usb/core/hcd.c (ffffffff8178042c)
Location: drivers/usb/core/hcd.c:435
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
In drivers/usb/core/hcd.c (ffffffff817bdc82)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (ffffffff817ee5e2)
Location: drivers/usb/core/hcd.c:438
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff818bdd95)
Location: drivers/usb/core/hcd.c:439
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff818ca8a6)
Location: drivers/usb/core/hcd.c:439
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
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
In drivers/usb/core/hcd.c (ffffffff818adced)
Location: drivers/usb/core/hcd.c:439
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
In drivers/usb/core/hcd.c (ffffffff81942db7)
Location: drivers/usb/core/hcd.c:439
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int rh_string(int id, const struct usb_hcd *hcd, u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a99640)
Location: drivers/usb/core/hcd.c:439
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
**Symbols:**

```
ffffffff81a99640-ffffffff81a997b5: rh_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int rh_string(int id, const struct usb_hcd *hcd, u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1da90)
Location: drivers/usb/core/hcd.c:439
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
**Symbols:**

```
ffffffff81c1da90-ffffffff81c1dc05: rh_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int rh_string(int id, const struct usb_hcd *hcd, u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c84980)
Location: drivers/usb/core/hcd.c:439
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
**Symbols:**

```
ffffffff81c84980-ffffffff81c84b03: rh_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int rh_string(int id, const struct usb_hcd *hcd, u8 *data, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d39380)
Location: drivers/usb/core/hcd.c:418
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:rh_call_control
```
**Symbols:**

```
ffffffff81d39380-ffffffff81d39503: rh_string (STB_LOCAL)
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
In drivers/usb/core/hcd.c (ffff800010a1d544)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (c0af4938)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (c000000000ad7988)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (ffffffe000641d58)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (ffffffff817a69c2)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (ffffffff81797de6)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (ffffffff817e3462)
Location: drivers/usb/core/hcd.c:438
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
In drivers/usb/core/hcd.c (ffffffff817fce8c)
Location: drivers/usb/core/hcd.c:438
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
