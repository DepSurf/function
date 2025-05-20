# Function: <code>dbc_write_complete</code>

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
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817747b0)
Location: drivers/usb/host/xhci-dbgtty.c:104
Inline: False
```
**Symbols:**

```
ffffffff817747b0-ffffffff81774845: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b4c80)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff817b4c80-ffffffff817b4d1d: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db1d0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff817db1d0-ffffffff817db26d: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff8181bbf0-ffffffff8181bc7d: dbc_write_complete (STB_LOCAL)
ffffffff8181c59c-ffffffff8181c5b4: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff8184cfc0-ffffffff8184d04d: dbc_write_complete (STB_LOCAL)
ffffffff8184d95c-ffffffff8184d974: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff8191fad0-ffffffff8191fb5d: dbc_write_complete (STB_LOCAL)
ffffffff8192052e-ffffffff81920546: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff819272b0-ffffffff81927338: dbc_write_complete (STB_LOCAL)
ffffffff81c228c2-ffffffff81c228d7: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff8190a880-ffffffff8190a908: dbc_write_complete (STB_LOCAL)
ffffffff81c14aa4-ffffffff81c14ab9: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff819aaf30-ffffffff819aafb8: dbc_write_complete (STB_LOCAL)
ffffffff81d21f96-ffffffff81d21fab: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81b09520-ffffffff81b095b4: dbc_write_complete (STB_LOCAL)
ffffffff81eedb9e-ffffffff81eedbb3: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c992b0)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81c992b0-ffffffff81c99352: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00660)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81d00660-ffffffff81d00702: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_dbc *dbc, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6160)
Location: drivers/usb/host/xhci-dbgtty.c:115
Inline: False
```
**Symbols:**

```
ffffffff81db6160-ffffffff81db6202: dbc_write_complete (STB_LOCAL)
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
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8cfe8)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffff800010a8cfe8-ffff800010a8d0dc: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f274)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
c0b5f274-c0b5f304: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68920)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
c000000000b68920-c000000000b689fc: dbc_write_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a1208)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffe0006a1208-ffffffe0006a12a6: dbc_write_complete (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff817ca510-ffffffff817ca59d: dbc_write_complete (STB_LOCAL)
ffffffff817caeac-ffffffff817caec4: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff81841e40-ffffffff81841ecd: dbc_write_complete (STB_LOCAL)
ffffffff818427dc-ffffffff818427f4: dbc_write_complete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dbc_write_complete(struct xhci_hcd *xhci, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:106
Inline: False
```
**Symbols:**

```
ffffffff8185c4e0-ffffffff8185c56d: dbc_write_complete (STB_LOCAL)
ffffffff8185cd3c-ffffffff8185cd54: dbc_write_complete.cold (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_dbc *dbc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xhci_hcd *xhci</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
