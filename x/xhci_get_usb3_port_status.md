# Function: <code>xhci_get_usb3_port_status</code>

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
In drivers/usb/host/xhci-hub.c (ffffffff817d3e64)
Location: drivers/usb/host/xhci-hub.c:908
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
In drivers/usb/host/xhci-hub.c (ffffffff81814293)
Location: drivers/usb/host/xhci-hub.c:918
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
In drivers/usb/host/xhci-hub.c (ffffffff81845454)
Location: drivers/usb/host/xhci-hub.c:927
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81917a00)
Location: drivers/usb/host/xhci-hub.c:930
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81917a00-ffffffff81917c2a: xhci_get_usb3_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff8191e330)
Location: drivers/usb/host/xhci-hub.c:930
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff8191e330-ffffffff8191e56a: xhci_get_usb3_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-hub.c (ffffffff81901a30)
Location: drivers/usb/host/xhci-hub.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81901a30-ffffffff81901c6f: xhci_get_usb3_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1018
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff819a1330-ffffffff819a156a: xhci_get_usb3_port_status (STB_LOCAL)
ffffffff81d218b8-ffffffff81d219b0: xhci_get_usb3_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1019
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81afec30-ffffffff81afeee3: xhci_get_usb3_port_status (STB_LOCAL)
ffffffff81eed506-ffffffff81eed613: xhci_get_usb3_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1033
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81c8dc50-ffffffff81c8df03: xhci_get_usb3_port_status (STB_LOCAL)
ffffffff820a5ad5-ffffffff820a5be2: xhci_get_usb3_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1033
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81cf4790-ffffffff81cf4a14: xhci_get_usb3_port_status (STB_LOCAL)
ffffffff82126f41-ffffffff82126fbd: xhci_get_usb3_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xhci_get_usb3_port_status(struct xhci_port *port, u32 *status, u32 portsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:1033
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81daa0d0-ffffffff81daa30c: xhci_get_usb3_port_status (STB_LOCAL)
ffffffff82208879-ffffffff822088fb: xhci_get_usb3_port_status.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (ffff800010a83fc0)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (c0b5745c)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (c000000000b5dc30)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (ffffffe000699f60)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (ffffffff817fd804)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (ffffffff817c29a4)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (ffffffff8183a2d4)
Location: drivers/usb/host/xhci-hub.c:927
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
In drivers/usb/host/xhci-hub.c (ffffffff81854764)
Location: drivers/usb/host/xhci-hub.c:927
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
