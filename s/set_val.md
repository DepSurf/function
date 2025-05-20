# Function: <code>set_val</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void set_val(u32 v, int where, int size, u32 *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-thunder-ecam.c (ffff800010738360)
Location: drivers/pci/controller/pci-thunder-ecam.c:16
Inline: False
Direct callers:
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:thunder_ecam_config_read
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
  - drivers/pci/controller/pci-thunder-ecam.c:handle_ea_bar
```
**Symbols:**

```
ffff800010738360-ffff800010738408: set_val (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
