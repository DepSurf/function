# Function: <code>finish_td</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, union xhci_trb *event_trb, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status, bool skip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8165ae10)
Location: drivers/usb/host/xhci-ring.c:1801
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8165ae10-ffffffff8165b090: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816bb6a0)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816bb6a0-ffffffff816bb930: finish_td.constprop.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e99b0)
Location: drivers/usb/host/xhci-ring.c:1841
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816e99b0-ffffffff816e9c82: finish_td.constprop.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fdef0)
Location: drivers/usb/host/xhci-ring.c:1932
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816fdef0-ffffffff816fdfd7: finish_td.isra.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8176aa70)
Location: drivers/usb/host/xhci-ring.c:1926
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8176aa70-ffffffff8176ab5a: finish_td.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817abdc0)
Location: drivers/usb/host/xhci-ring.c:1849
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff817abdc0-ffffffff817abeaa: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d1e20)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff817d1e20-ffffffff817d1f0a: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81811770)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81811770-ffffffff81811878: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81842970)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81842970-ffffffff81842a78: finish_td (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81912610)
Location: drivers/usb/host/xhci-ring.c:1969
Inline: True
```
**Symbols:**

```
ffffffff81912610-ffffffff81912787: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81919c80)
Location: drivers/usb/host/xhci-ring.c:1974
Inline: True
```
**Symbols:**

```
ffffffff81919c80-ffffffff81919df7: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff818fd030)
Location: drivers/usb/host/xhci-ring.c:2137
Inline: True
```
**Symbols:**

```
ffffffff818fd030-ffffffff818fd188: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8199c180)
Location: drivers/usb/host/xhci-ring.c:2202
Inline: True
```
**Symbols:**

```
ffffffff8199c180-ffffffff8199c2d5: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81af9650)
Location: drivers/usb/host/xhci-ring.c:2136
Inline: True
```
**Symbols:**

```
ffffffff81af9650-ffffffff81af97cd: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c87780)
Location: drivers/usb/host/xhci-ring.c:2138
Inline: True
```
**Symbols:**

```
ffffffff81c87780-ffffffff81c878fd: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cee950)
Location: drivers/usb/host/xhci-ring.c:2160
Inline: True
```
**Symbols:**

```
ffffffff81cee950-ffffffff81ceeabe: finish_td.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da3f50)
Location: drivers/usb/host/xhci-ring.c:2165
Inline: True
```
**Symbols:**

```
ffffffff81da3f50-ffffffff81da40be: finish_td.isra.0 (STB_LOCAL)
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
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a81960)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffff800010a81960-ffff800010a81a90: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b54e54)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
c0b54e54-c0b54f4c: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5ad80)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
c000000000b5ad80-c000000000b5af74: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697fc0)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffe000697fc0-ffffffe0006980cc: finish_td (STB_LOCAL)
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
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817fad20)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff817fad20-ffffffff817fae28: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bfec0)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff817bfec0-ffffffff817bffc8: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818377f0)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff818377f0-ffffffff818378f8: finish_td (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int finish_td(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_transfer_event *event, struct xhci_virt_ep *ep, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81851c20)
Location: drivers/usb/host/xhci-ring.c:1943
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81851c20-ffffffff81851d28: finish_td (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
