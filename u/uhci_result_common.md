# Function: <code>uhci_result_common</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff816478a6)
Location: drivers/usb/host/uhci-q.c:1171
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff816a819f)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d62bf)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff816ea82e)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff8175701e)
Location: drivers/usb/host/uhci-q.c:1171
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff8179871a)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bebea)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff817fe554)
Location: drivers/usb/host/uhci-q.c:1170
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182f3a4)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff818ff980-ffffffff818ffd3e: uhci_result_common (STB_LOCAL)
ffffffff819031bc-ffffffff81903225: uhci_result_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81908250-ffffffff8190860e: uhci_result_common (STB_LOCAL)
ffffffff81c207d7-ffffffff81c20840: uhci_result_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff818eba30-ffffffff818ebdea: uhci_result_common (STB_LOCAL)
ffffffff81c12841-ffffffff81c128aa: uhci_result_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81988140-ffffffff819884fa: uhci_result_common (STB_LOCAL)
ffffffff81d1f334-ffffffff81d1f39d: uhci_result_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81ae4c60-ffffffff81ae5056: uhci_result_common (STB_LOCAL)
ffffffff81eeaeb6-ffffffff81eeaf30: uhci_result_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70860)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81c70860-ffffffff81c70c56: uhci_result_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd7e50)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81cd7e50-ffffffff81cd823a: uhci_result_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uhci_result_common(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8ce60)
Location: drivers/usb/host/uhci-q.c:1170
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81d8ce60-ffffffff81d8d24a: uhci_result_common (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffff800010a69d2c)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (c0b3b968)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (c000000000b3ac28)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffe000684d0e)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e7784)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81824224)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183cf54)
Location: drivers/usb/host/uhci-q.c:1170
Inline: True
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
