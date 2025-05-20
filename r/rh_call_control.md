# Function: <code>rh_call_control</code>

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
In drivers/usb/core/hcd.c (ffffffff8160e811)
Location: drivers/usb/core/hcd.c:486
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
In drivers/usb/core/hcd.c (ffffffff8166e433)
Location: drivers/usb/core/hcd.c:485
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
In drivers/usb/core/hcd.c (ffffffff8169c113)
Location: drivers/usb/core/hcd.c:486
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
In drivers/usb/core/hcd.c (ffffffff816b14a9)
Location: drivers/usb/core/hcd.c:487
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
In drivers/usb/core/hcd.c (ffffffff8171cad8)
Location: drivers/usb/core/hcd.c:474
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
In drivers/usb/core/hcd.c (ffffffff8175b678)
Location: drivers/usb/core/hcd.c:474
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
In drivers/usb/core/hcd.c (ffffffff8177fba4)
Location: drivers/usb/core/hcd.c:474
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817bd420)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff817bd420-ffffffff817bdeac: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817edd80)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff817edd80-ffffffff817ee80c: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bd530)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff818bd530-ffffffff818bdf4c: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ca120)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff818ca120-ffffffff818cab4b: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818ad460)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff818ad460-ffffffff818adecb: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81942530)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff81942530-ffffffff81942f95: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81a9a460)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff81a9a460-ffffffff81a9abf5: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1ec50)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff81c1ec50-ffffffff81c1f3f5: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c85b50)
Location: drivers/usb/core/hcd.c:478
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff81c85b50-ffffffff81c86364: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3a5e0)
Location: drivers/usb/core/hcd.c:457
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff81d3a5e0-ffffffff81d3ae02: rh_call_control (STB_LOCAL)
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
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1ce10)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffff800010a1ce10-ffff800010a1d6fc: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af4300)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
c0af4300-c0af4ad4: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad7110)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
c000000000ad7110-c000000000ad7b38: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe00064184a)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffe00064184a-ffffffe000641f60: rh_call_control (STB_LOCAL)
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
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817a6160)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff817a6160-ffffffff817a6bec: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81797590)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff81797590-ffffffff81798010: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817e2c00)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff817e2c00-ffffffff817e368c: rh_call_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rh_call_control(struct usb_hcd *hcd, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff817fc6a0)
Location: drivers/usb/core/hcd.c:477
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_hcd_submit_urb
```
**Symbols:**

```
ffffffff817fc6a0-ffffffff817fd0b1: rh_call_control (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
