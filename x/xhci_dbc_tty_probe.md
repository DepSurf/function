# Function: <code>xhci_dbc_tty_probe</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819278d0)
Location: drivers/usb/host/xhci-dbgtty.c:473
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff819278d0-ffffffff8192796a: xhci_dbc_tty_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:473
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81c14aec-ffffffff81c14b09: xhci_dbc_tty_probe.cold (STB_LOCAL)
ffffffff8190aea0-ffffffff8190afe5: xhci_dbc_tty_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_dbc_tty_probe(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: drivers/usb/host/xhci-dbgtty.c:471
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81d22007-ffffffff81d22024: xhci_dbc_tty_probe.cold (STB_LOCAL)
ffffffff819ab7b0-ffffffff819ab8ed: xhci_dbc_tty_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device *dev, void *base, struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09b70)
Location: drivers/usb/host/xhci-dbgtty.c:493
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
**Symbols:**

```
ffffffff81b09b70-ffffffff81b09c0b: xhci_dbc_tty_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device *dev, void *base, struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99950)
Location: drivers/usb/host/xhci-dbgtty.c:493
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
**Symbols:**

```
ffffffff81c99950-ffffffff81c999eb: xhci_dbc_tty_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device *dev, void *base, struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00d00)
Location: drivers/usb/host/xhci-dbgtty.c:493
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
**Symbols:**

```
ffffffff81d00d00-ffffffff81d00d9b: xhci_dbc_tty_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_dbc_tty_probe(struct device *dev, void *base, struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6800)
Location: drivers/usb/host/xhci-dbgtty.c:492
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
**Symbols:**

```
ffffffff81db6800-ffffffff81db68cd: xhci_dbc_tty_probe (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>void *base</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci</code> ➡️ <code>dev, base, xhci</code>
</li>
</ul>
</details>
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
