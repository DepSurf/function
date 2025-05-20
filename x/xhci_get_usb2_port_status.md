# Function: <code>xhci_get_usb2_port_status</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff817d3ff3)
Location: drivers/usb/host/xhci-hub.c:949
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff818143e8)
Location: drivers/usb/host/xhci-hub.c:959
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff8184553b)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff81918988)
Location: drivers/usb/host/xhci-hub.c:981
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff8191f2b9)
Location: drivers/usb/host/xhci-hub.c:981
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff819029d9)
Location: drivers/usb/host/xhci-hub.c:1067
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff819a2744)
Location: drivers/usb/host/xhci-hub.c:1069
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb2_port_status(struct xhci_port *port, u32 *status, u32 portsc, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1070
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81b000d0-ffffffff81b0023f: xhci_get_usb2_port_status (STB_LOCAL)
ffffffff81eed678-ffffffff81eed6cd: xhci_get_usb2_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb2_port_status(struct xhci_port *port, u32 *status, u32 portsc, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1084
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81c8f000-ffffffff81c8f16f: xhci_get_usb2_port_status (STB_LOCAL)
ffffffff820a5c13-ffffffff820a5c68: xhci_get_usb2_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb2_port_status(struct xhci_port *port, u32 *status, u32 portsc, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1084
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81cf5950-ffffffff81cf5a9c: xhci_get_usb2_port_status (STB_LOCAL)
ffffffff82126ff4-ffffffff82127024: xhci_get_usb2_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb2_port_status(struct xhci_port *port, u32 *status, u32 portsc, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1084
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81dab240-ffffffff81dab3c8: xhci_get_usb2_port_status (STB_LOCAL)
ffffffff82208932-ffffffff8220897b: xhci_get_usb2_port_status.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (ffff800010a840e8)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (c0b5751c)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (c000000000b5dd00)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffe00069a09a)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff817fd8eb)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff817c2a8b)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff8183a3bb)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff8185484b)
Location: drivers/usb/host/xhci-hub.c:978
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
