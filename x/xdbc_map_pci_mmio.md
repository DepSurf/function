# Function: <code>xdbc_map_pci_mmio</code>

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
In drivers/usb/early/xhci-dbc.c (ffffffff828ea854)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
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
In drivers/usb/early/xhci-dbc.c (ffffffff82905295)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
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
In drivers/usb/early/xhci-dbc.c (ffffffff8290ecd0)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22913)
Location: drivers/usb/early/xhci-dbc.c:37
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff82d22913-ffffffff82d22ac2: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8301070c)
Location: drivers/usb/early/xhci-dbc.c:39
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8301070c-ffffffff830108bb: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8321b6e7)
Location: drivers/usb/early/xhci-dbc.c:39
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8321b6e7-ffffffff8321b896: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8330531a)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8330531a-ffffffff833054e5: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff834be43b)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff834be43b-ffffffff834be612: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83efc360)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff83efc360-ffffffff83efc57b: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83722160)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff83722160-ffffffff8372237b: xdbc_map_pci_mmio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xdbc_map_pci_mmio(u32 bus, u32 dev, u32 func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83955f90)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff83955f90-ffffffff839561ab: xdbc_map_pci_mmio (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fd32)
Location: drivers/usb/early/xhci-dbc.c:38
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
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
