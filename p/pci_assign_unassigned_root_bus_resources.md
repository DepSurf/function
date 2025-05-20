# Function: <code>pci_assign_unassigned_root_bus_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81440960)
Location: drivers/pci/setup-bus.c:1688
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81440960-ffffffff81440c1b: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148c870)
Location: drivers/pci/setup-bus.c:1760
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8148c870-ffffffff8148cb31: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814ae060)
Location: drivers/pci/setup-bus.c:1761
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814ae060-ffffffff814ae321: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b8400)
Location: drivers/pci/setup-bus.c:1752
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814b8400-ffffffff814b86bb: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f85a0)
Location: drivers/pci/setup-bus.c:1755
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff814f85a0-ffffffff814f885b: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81528fe0)
Location: drivers/pci/setup-bus.c:1750
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81528fe0-ffffffff815292af: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153ee80)
Location: drivers/pci/setup-bus.c:1752
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8153ee80-ffffffff8153f14f: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8156ec23-ffffffff8156ed43: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff8156e2e0-ffffffff8156e4a9: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8158fc18-ffffffff8158fd5b: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff8158f2c0-ffffffff8158f489: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1752
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81637743-ffffffff81637867: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff81636ce0-ffffffff81636ede: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1753
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81bf8bac-ffffffff81bf8cd0: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff8165bda0-ffffffff8165bf9e: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1753
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81beaa06-ffffffff81beab28: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff8163e340-ffffffff8163e53e: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1753
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81ce5888-ffffffff81ce59bf: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff816aeea0-ffffffff816af0ad: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1753
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81eac357-ffffffff81eac48b: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff817d2340-ffffffff817d254e: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2044
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8208f412-ffffffff8208f427: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff818f29a0-ffffffff818f2d93: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2035
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8210f7be-ffffffff8210f7d3: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff81935dc0-ffffffff819361b3: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:2045
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff821ed454-ffffffff821ed469: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff8197eb70-ffffffff8197ef63: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
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
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f4778)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - arch/arm64/kernel/pci.c:pci_acpi_scan_root
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffff8000106f4778-ffff8000106f4a4c: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088f1f0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
**Symbols:**

```
c088f1f0-c088f514: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000872f20)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
**Symbols:**

```
c000000000872f20-c0000000008732a0: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c7814)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
```
**Symbols:**

```
ffffffe0004c7814-ffffffe0004c7a66: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81583a9c-ffffffff81583bdf: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff81583140-ffffffff81583309: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81572878-ffffffff815729bb: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff81571f20-ffffffff815720e9: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff81583968-ffffffff81583aab: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff81583010-ffffffff815831d9: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_assign_unassigned_root_bus_resources(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1715
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_resources
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
**Symbols:**

```
ffffffff8159de18-ffffffff8159df5b: pci_assign_unassigned_root_bus_resources.cold (STB_LOCAL)
ffffffff8159d4c0-ffffffff8159d689: pci_assign_unassigned_root_bus_resources (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
