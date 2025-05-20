# Function: <code>xhci_handle_usb2_port_link_resume</code>

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
In drivers/usb/host/xhci-hub.c (ffffffff817d4136)
Location: drivers/usb/host/xhci-hub.c:798
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
In drivers/usb/host/xhci-hub.c (ffffffff8181457e)
Location: drivers/usb/host/xhci-hub.c:807
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
In drivers/usb/host/xhci-hub.c (ffffffff818457af)
Location: drivers/usb/host/xhci-hub.c:816
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
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
In drivers/usb/host/xhci-hub.c (ffffffff819184f0)
Location: drivers/usb/host/xhci-hub.c:819
Inline: True
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff819184f0-ffffffff819187c5: xhci_handle_usb2_port_link_resume.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (ffffffff8191ee10)
Location: drivers/usb/host/xhci-hub.c:819
Inline: True
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff8191ee10-ffffffff8191f0e2: xhci_handle_usb2_port_link_resume.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (ffffffff81902530)
Location: drivers/usb/host/xhci-hub.c:905
Inline: True
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff81902530-ffffffff81902805: xhci_handle_usb2_port_link_resume.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:907
Inline: True
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
```
**Symbols:**

```
ffffffff819a2070-ffffffff819a259c: xhci_handle_usb2_port_link_resume.isra.0 (STB_LOCAL)
ffffffff81d219e5-ffffffff81d21a1b: xhci_handle_usb2_port_link_resume.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:908
Inline: True
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
```
**Symbols:**

```
ffffffff81affb80-ffffffff81b000c1: xhci_handle_usb2_port_link_resume.isra.0 (STB_LOCAL)
ffffffff81eed647-ffffffff81eed678: xhci_handle_usb2_port_link_resume.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:922
Inline: True
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
```
**Symbols:**

```
ffffffff81c8eab0-ffffffff81c8efe7: xhci_handle_usb2_port_link_resume.isra.0 (STB_LOCAL)
ffffffff820a5be2-ffffffff820a5c13: xhci_handle_usb2_port_link_resume.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_handle_usb2_port_link_resume(struct xhci_port *port, u32 portsc, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:926
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
```
**Symbols:**

```
ffffffff81cf5550-ffffffff81cf5939: xhci_handle_usb2_port_link_resume (STB_LOCAL)
ffffffff82126fbd-ffffffff82126ff4: xhci_handle_usb2_port_link_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_handle_usb2_port_link_resume(struct xhci_port *port, u32 portsc, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-hub.c (0)
Location: drivers/usb/host/xhci-hub.c:926
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_get_usb2_port_status
```
**Symbols:**

```
ffffffff81daae40-ffffffff81dab229: xhci_handle_usb2_port_link_resume (STB_LOCAL)
ffffffff822088fb-ffffffff82208932: xhci_handle_usb2_port_link_resume.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-hub.c (ffff800010a8427c)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (c0b57750)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (c000000000b5e12c)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (ffffffe00069a28e)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (ffffffff817fdb5f)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (ffffffff817c2cff)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (ffffffff8183a62f)
Location: drivers/usb/host/xhci-hub.c:816
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
In drivers/usb/host/xhci-hub.c (ffffffff81854abf)
Location: drivers/usb/host/xhci-hub.c:816
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
