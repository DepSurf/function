# Function: <code>xhci_remove_dbc_dev</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_remove_dbc_dev(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b08be0)
Location: drivers/usb/host/xhci-dbgcap.c:1045
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_stop
```
**Symbols:**

```
ffffffff81b08be0-ffffffff81b08c31: xhci_remove_dbc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_remove_dbc_dev(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98830)
Location: drivers/usb/host/xhci-dbgcap.c:1045
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_stop
```
**Symbols:**

```
ffffffff81c98830-ffffffff81c98881: xhci_remove_dbc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_remove_dbc_dev(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cffbc0)
Location: drivers/usb/host/xhci-dbgcap.c:1228
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_stop
```
**Symbols:**

```
ffffffff81cffbc0-ffffffff81cffc11: xhci_remove_dbc_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_remove_dbc_dev(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db5660)
Location: drivers/usb/host/xhci-dbgcap.c:1234
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_stop
```
**Symbols:**

```
ffffffff81db5660-ffffffff81db56b1: xhci_remove_dbc_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
