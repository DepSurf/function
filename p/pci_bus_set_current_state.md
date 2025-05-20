# Function: <code>pci_bus_set_current_state</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c642)
Location: drivers/pci/pci.c:869
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff8151cb90-ffffffff8151cbb7: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531f32)
Location: drivers/pci/pci.c:1040
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81532290-ffffffff815322b7: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815615c2)
Location: drivers/pci/pci.c:1066
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81561960-ffffffff81561987: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582772)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81582ab0-ffffffff81582ad7: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816291f6)
Location: drivers/pci/pci.c:1143
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff816296a0-ffffffff816296c7: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f446)
Location: drivers/pci/pci.c:1277
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff8164fa70-ffffffff8164fa97: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631f14)
Location: drivers/pci/pci.c:1307
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81632620-ffffffff81632647: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a1834)
Location: drivers/pci/pci.c:1317
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff816a1cf0-ffffffff816a1d17: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c38bc)
Location: drivers/pci/pci.c:1337
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff817c3d10-ffffffff817c3d41: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e071d)
Location: drivers/pci/pci.c:1318
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff818e0be0-ffffffff818e0c11: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81923bac)
Location: drivers/pci/pci.c:1356
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81924020-ffffffff81924051: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196c6f0)
Location: drivers/pci/pci.c:1426
Inline: False
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff8196c6f0-ffffffff8196c721: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e634c)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffff8000106e6728-ffff8000106e6768: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881670)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
c0881a28-c0881a64: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008605a4)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
c000000000860b40-c000000000860b8c: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bcdf4)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffe0004bd0f8-ffffffe0004bd134: pci_bus_set_current_state (STB_GLOBAL)
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
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576c92)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81576fd0-ffffffff81576ff7: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815653f2)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81565730-ffffffff81565757: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815764c2)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81576800-ffffffff81576827: pci_bus_set_current_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_set_current_state(struct pci_bus *bus, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815909a2)
Location: drivers/pci/pci.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
Direct callers:
  - drivers/gpu/vga/vga_switcheroo.c:vga_switcheroo_runtime_suspend
```
**Symbols:**

```
ffffffff81590ce0-ffffffff81590d07: pci_bus_set_current_state (STB_GLOBAL)
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
