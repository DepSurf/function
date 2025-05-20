# Function: <code>pci_wakeup_bus</code>

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
In drivers/pci/pci.c (ffffffff814366bc)
Location: drivers/pci/pci.c:761
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
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
In drivers/pci/pci.c (ffffffff814821af)
Location: drivers/pci/pci.c:782
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
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
In drivers/pci/pci.c (ffffffff814a373f)
Location: drivers/pci/pci.c:807
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
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
In drivers/pci/pci.c (ffffffff814ad78f)
Location: drivers/pci/pci.c:802
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
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
In drivers/pci/pci.c (ffffffff814ecb5f)
Location: drivers/pci/pci.c:803
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c72f)
Location: drivers/pci/pci.c:815
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff8151cb70-ffffffff8151cb8f: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8153201f)
Location: drivers/pci/pci.c:986
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81532270-ffffffff8153228f: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815616bc)
Location: drivers/pci/pci.c:1012
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81561940-ffffffff8156195f: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582b05)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81582a90-ffffffff81582aaf: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162915d)
Location: drivers/pci/pci.c:1053
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81629630-ffffffff8162964f: pci_wakeup_bus (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6798)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffff8000106e66e8-ffff8000106e6724: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881a94)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
c08819f8-c0881a28: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000860bcc)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
c000000000860af0-c000000000860b38: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd164)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffe0004bd0c2-ffffffe0004bd0f8: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577025)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81576fb0-ffffffff81576fcf: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565785)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81565710-ffffffff8156572f: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576855)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff815767e0-ffffffff815767ff: pci_wakeup_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_wakeup_bus(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590d35)
Location: drivers/pci/pci.c:999
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_resume
```
**Symbols:**

```
ffffffff81590cc0-ffffffff81590cdf: pci_wakeup_bus (STB_GLOBAL)
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
