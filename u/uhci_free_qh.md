# Function: <code>uhci_free_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81644b10)
Location: drivers/usb/host/uhci-q.c:293
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81644b10-ffffffff81644bf7: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a5660)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff816a5660-ffffffff816a574a: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d3760)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff816d3760-ffffffff816d384a: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e7e00)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff816e7e00-ffffffff816e7ecb: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817545e0)
Location: drivers/usb/host/uhci-q.c:293
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff817545e0-ffffffff817546a9: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81794c30)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81794c30-ffffffff81794cf9: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bb0f0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff817bb0f0-ffffffff817bb1b9: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff817faa20-ffffffff817faaf4: uhci_free_qh (STB_LOCAL)
ffffffff817fff1e-ffffffff817fff31: uhci_free_qh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182b860)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff8182b860-ffffffff8182b932: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fd930)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
```
**Symbols:**

```
ffffffff818fd930-ffffffff818fda02: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81906210)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:release_uhci
```
**Symbols:**

```
ffffffff81906210-ffffffff819062e2: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9840)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff818e9840-ffffffff818e9912: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81985ee0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81985ee0-ffffffff81985fb2: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae1da0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81ae1da0-ffffffff81ae1e78: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6d780)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81c6d780-ffffffff81c6d858: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd4d90)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81cd4d90-ffffffff81cd4e68: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d89d70)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff81d89d70-ffffffff81d89e48: uhci_free_qh (STB_LOCAL)
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
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a670b0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffff800010a670b0-ffff800010a67190: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b38f64)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
c0b38f64-c0b39068: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b381f0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
c000000000b381f0-c000000000b38328: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000681176)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffe000681176-ffffffe00068121e: uhci_free_qh (STB_LOCAL)
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
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e3c40)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff817e3c40-ffffffff817e3d12: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818206e0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff818206e0-ffffffff818207b2: uhci_free_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_free_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183a7f0)
Location: drivers/usb/host/uhci-q.c:292
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_endpoint_disable
  - drivers/usb/host/uhci-hcd.c:uhci_stop
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff8183a7f0-ffffffff8183a8c2: uhci_free_qh (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
