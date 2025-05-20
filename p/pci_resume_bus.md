# Function: <code>pci_resume_bus</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f3ad)
Location: drivers/pci/pci.c:1187
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff8164fa00-ffffffff8164fa1f: pci_resume_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631e7c)
Location: drivers/pci/pci.c:1217
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff816325b0-ffffffff816325cf: pci_resume_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a179c)
Location: drivers/pci/pci.c:1227
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff816a1c80-ffffffff816a1c9f: pci_resume_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c34f0)
Location: drivers/pci/pci.c:1159
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff817c34f0-ffffffff817c3523: pci_resume_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e0300)
Location: drivers/pci/pci.c:1143
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff818e0300-ffffffff818e0333: pci_resume_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81923760)
Location: drivers/pci/pci.c:1157
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81923760-ffffffff81923793: pci_resume_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_resume_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196bd80)
Location: drivers/pci/pci.c:1220
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff8196bd80-ffffffff8196bdb3: pci_resume_bus (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
