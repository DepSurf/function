# Function: <code>xhci_add_in_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816533b5)
Location: drivers/usb/host/xhci-mem.c:2054
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b3a43)
Location: drivers/usb/host/xhci-mem.c:2076
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e1bf3)
Location: drivers/usb/host/xhci-mem.c:2109
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f5de3)
Location: drivers/usb/host/xhci-mem.c:2048
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81762763)
Location: drivers/usb/host/xhci-mem.c:2090
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a6570)
Location: drivers/usb/host/xhci-mem.c:2111
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cc58b)
Location: drivers/usb/host/xhci-mem.c:2111
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
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
In drivers/usb/host/xhci-mem.c (ffffffff8180952f)
Location: drivers/usb/host/xhci-mem.c:2111
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (ffffffff8183a437)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff8190bcb0-ffffffff8190bfc0: xhci_add_in_port (STB_LOCAL)
ffffffff8190ffa6-ffffffff81910034: xhci_add_in_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2129
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff81913730-ffffffff81913a3b: xhci_add_in_port (STB_LOCAL)
ffffffff81c21649-ffffffff81c216e3: xhci_add_in_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2117
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff818f6c30-ffffffff818f6f42: xhci_add_in_port (STB_LOCAL)
ffffffff81c136fe-ffffffff81c13791: xhci_add_in_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2117
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff81995050-ffffffff8199535f: xhci_add_in_port (STB_LOCAL)
ffffffff81d20524-ffffffff81d205b7: xhci_add_in_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:2105
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff81af1d30-ffffffff81af2069: xhci_add_in_port (STB_LOCAL)
ffffffff81eec075-ffffffff81eec105: xhci_add_in_port.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c7ef20)
Location: drivers/usb/host/xhci-mem.c:2114
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff81c7ef20-ffffffff81c7f33f: xhci_add_in_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce61a0)
Location: drivers/usb/host/xhci-mem.c:1959
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff81ce61a0-ffffffff81ce6612: xhci_add_in_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9b400)
Location: drivers/usb/host/xhci-mem.c:2002
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
**Symbols:**

```
ffffffff81d9b400-ffffffff81d9b872: xhci_add_in_port (STB_LOCAL)
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
void xhci_add_in_port(struct xhci_hcd *xhci, unsigned int num_ports, __le32 *addr, int max_caps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a77f80)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
**Symbols:**

```
ffff800010a77f80-ffff800010a78360: xhci_add_in_port (STB_LOCAL)
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
In drivers/usb/host/xhci-mem.c (c0b4bab8)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (c000000000b4ea88)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (ffffffe00068f9c8)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (ffffffff817f27e7)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (ffffffff817b7987)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (ffffffff8182f2b7)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
In drivers/usb/host/xhci-mem.c (ffffffff81849427)
Location: drivers/usb/host/xhci-mem.c:2121
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
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
<b>Arch</b>
<ul>
</ul>
