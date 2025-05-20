# Function: <code>dbc_ring_free</code>

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
void dbc_ring_free(struct device *dev, struct xhci_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925480)
Location: drivers/usb/host/xhci-dbgcap.c:26
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff81925480-ffffffff819254cc: dbc_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dbc_ring_free(struct device *dev, struct xhci_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81908b80)
Location: drivers/usb/host/xhci-dbgcap.c:26
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff81908b80-ffffffff81908bcc: dbc_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dbc_ring_free(struct device *dev, struct xhci_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9400)
Location: drivers/usb/host/xhci-dbgcap.c:26
Inline: False
```
**Symbols:**

```
ffffffff819a9400-ffffffff819a944c: dbc_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dbc_ring_free(struct device *dev, struct xhci_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07490)
Location: drivers/usb/host/xhci-dbgcap.c:26
Inline: False
```
**Symbols:**

```
ffffffff81b07490-ffffffff81b074fc: dbc_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dbc_ring_free(struct device *dev, struct xhci_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c96d40)
Location: drivers/usb/host/xhci-dbgcap.c:26
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
```
**Symbols:**

```
ffffffff81c96d40-ffffffff81c96dac: dbc_ring_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dbc_ring_free(struct device *dev, struct xhci_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe0d0)
Location: drivers/usb/host/xhci-dbgcap.c:26
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
```
**Symbols:**

```
ffffffff81cfe0d0-ffffffff81cfe13c: dbc_ring_free (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4872)
Location: drivers/usb/host/xhci-dbgcap.c:41
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_mem_cleanup
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
