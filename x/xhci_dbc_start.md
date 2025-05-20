# Function: <code>xhci_dbc_start</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772d70)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81772d70-ffffffff8177333d: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3340)
Location: drivers/usb/host/xhci-dbgcap.c:525
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff817b3340-ffffffff817b3950: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9920)
Location: drivers/usb/host/xhci-dbgcap.c:524
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff817d9920-ffffffff817d9e68: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:522
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8181a6d0-ffffffff8181a80f: xhci_dbc_start (STB_LOCAL)
ffffffff8181b4c9-ffffffff8181b4dc: xhci_dbc_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184ba40)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8184ba40-ffffffff8184bb86: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e660)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8191e660-ffffffff8191e6f6: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925a90)
Location: drivers/usb/host/xhci-dbgcap.c:608
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81925a90-ffffffff81925b86: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909180)
Location: drivers/usb/host/xhci-dbgcap.c:608
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81909180-ffffffff81909277: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9a00)
Location: drivers/usb/host/xhci-dbgcap.c:608
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff819a9a00-ffffffff819a9af7: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07ad0)
Location: drivers/usb/host/xhci-dbgcap.c:608
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81b07ad0-ffffffff81b07be3: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c973c0)
Location: drivers/usb/host/xhci-dbgcap.c:608
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81c973c0-ffffffff81c974d3: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe6e0)
Location: drivers/usb/host/xhci-dbgcap.c:608
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81cfe6e0-ffffffff81cfe7f9: xhci_dbc_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4f40)
Location: drivers/usb/host/xhci-dbgcap.c:619
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81db4f40-ffffffff81db5059: xhci_dbc_start.isra.0 (STB_LOCAL)
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
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8adc0)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffff800010a8adc0-ffff800010a8af74: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5dad4)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
c0b5dad4-c0b5dc2c: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66760)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
c000000000b66760-c000000000b66988: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a031c)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffe0006a031c-ffffffe0006a04a8: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8f90)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff817c8f90-ffffffff817c90d6: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818408c0)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff818408c0-ffffffff81840a06: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_dbc_start(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185ad90)
Location: drivers/usb/host/xhci-dbgcap.c:521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_resume
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8185ad90-ffffffff8185aed6: xhci_dbc_start (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
