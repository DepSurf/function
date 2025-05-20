# Function: <code>vga_is_boot_device</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool vga_is_boot_device(struct vga_device *vgadev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vgaarb.c (0)
Location: drivers/pci/vgaarb.c:600
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
```
**Symbols:**

```
ffffffff817f3d10-ffffffff817f3fbc: vga_is_boot_device (STB_LOCAL)
ffffffff81eb2286-ffffffff81eb22a3: vga_is_boot_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool vga_is_boot_device(struct vga_device *vgadev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vgaarb.c (0)
Location: drivers/pci/vgaarb.c:600
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
```
**Symbols:**

```
ffffffff8191e3a0-ffffffff8191e64c: vga_is_boot_device (STB_LOCAL)
ffffffff82090018-ffffffff82090035: vga_is_boot_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool vga_is_boot_device(struct vga_device *vgadev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vgaarb.c (0)
Location: drivers/pci/vgaarb.c:593
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
```
**Symbols:**

```
ffffffff81961750-ffffffff81961971: vga_is_boot_device (STB_LOCAL)
ffffffff8211036c-ffffffff82110389: vga_is_boot_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool vga_is_boot_device(struct vga_device *vgadev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vgaarb.c (0)
Location: drivers/pci/vgaarb.c:604
Inline: False
Direct callers:
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
```
**Symbols:**

```
ffffffff819ab0a0-ffffffff819ab2b7: vga_is_boot_device (STB_LOCAL)
ffffffff821ee0a8-ffffffff821ee0c5: vga_is_boot_device.cold (STB_LOCAL)
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
