# Function: <code>usb_amd_pt_check_port</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81780a50)
Location: drivers/usb/host/pci-quirks.c:538
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff81780a50-ffffffff81780bfa: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817a7270)
Location: drivers/usb/host/pci-quirks.c:538
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff817a7270-ffffffff817a741a: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817e6480)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff817e6480-ffffffff817e6628: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81817340)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff81817340-ffffffff818174e8: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818e83c0)
Location: drivers/usb/host/pci-quirks.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff818e83c0-ffffffff818e8568: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818f13a0)
Location: drivers/usb/host/pci-quirks.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff818f13a0-ffffffff818f154b: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818d4ba0)
Location: drivers/usb/host/pci-quirks.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff818d4ba0-ffffffff818d4d4b: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff81d1e74f-ffffffff81d1e76f: usb_amd_pt_check_port.cold (STB_LOCAL)
ffffffff8196f620-ffffffff8196f7d9: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff81eea212-ffffffff81eea22c: usb_amd_pt_check_port.cold (STB_LOCAL)
ffffffff81ac9b20-ffffffff81ac9ce1: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff820a5262-ffffffff820a527c: usb_amd_pt_check_port.cold (STB_LOCAL)
ffffffff81c53fd0-ffffffff81c54191: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:548
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff82126787-ffffffff821267a1: usb_amd_pt_check_port.cold (STB_LOCAL)
ffffffff81cbb5a0-ffffffff81cbb761: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/pci-quirks.c (0)
Location: drivers/usb/host/pci-quirks.c:506
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff82207f90-ffffffff82207faa: usb_amd_pt_check_port.cold (STB_LOCAL)
ffffffff81d70110-ffffffff81d702d1: usb_amd_pt_check_port (STB_GLOBAL)
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
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffff800010a4fb48)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffff800010a4fb48-ffff800010a4fd40: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c0b22640)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
c0b22640-c0b22808: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c000000000b18220)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
c000000000b18220-c000000000b18484: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffe00066cc94)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffe00066cc94-ffffffe00066ce66: usb_amd_pt_check_port (STB_GLOBAL)
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
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817cf720)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff817cf720-ffffffff817cf8c8: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817ad650)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff817ad650-ffffffff817ad7f8: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8180c1c0)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff8180c1c0-ffffffff8180c368: usb_amd_pt_check_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool usb_amd_pt_check_port(struct device *device, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818262d0)
Location: drivers/usb/host/pci-quirks.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-hub.c:xhci_bus_suspend
```
**Symbols:**

```
ffffffff818262d0-ffffffff81826478: usb_amd_pt_check_port (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
