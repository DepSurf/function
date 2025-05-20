# Function: <code>pci_bus_release_bridge_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e690)
Location: drivers/pci/setup-bus.c:1531
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff8143e690-ffffffff8143e84b: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148a500)
Location: drivers/pci/setup-bus.c:1603
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8148a500-ffffffff8148a6bc: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814abcf0)
Location: drivers/pci/setup-bus.c:1604
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff814abcf0-ffffffff814abeac: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b6030)
Location: drivers/pci/setup-bus.c:1595
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff814b6030-ffffffff814b61dd: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f5a30)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff814f5a30-ffffffff814f5bdd: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81526720)
Location: drivers/pci/setup-bus.c:1593
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff81526720-ffffffff815268cd: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153c6f0)
Location: drivers/pci/setup-bus.c:1595
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8153c6f0-ffffffff8153c8a1: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8156be40-ffffffff8156bf6b: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff8156e9b0-ffffffff8156ea17: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8158ce20-ffffffff8158cf4b: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff8158f983-ffffffff8158f9ea: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1590
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff81633ed0-ffffffff81633ffb: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff816374e1-ffffffff81637548: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1591
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff81658f80-ffffffff816590ab: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff81bf8943-ffffffff81bf89aa: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1591
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8163b3f0-ffffffff8163b51b: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff81bea77d-ffffffff81bea7e4: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1591
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff816abe20-ffffffff816abf4b: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff81ce55ff-ffffffff81ce5666: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1591
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff817cf230-ffffffff817cf356: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff81eac0ca-ffffffff81eac129: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818ef020)
Location: drivers/pci/setup-bus.c:1591
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff818ef020-ffffffff818ef213: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff819324f0)
Location: drivers/pci/setup-bus.c:1584
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff819324f0-ffffffff819326e3: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197b340)
Location: drivers/pci/setup-bus.c:1594
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8197b340-ffffffff8197b533: pci_bus_release_bridge_resources (STB_LOCAL)
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
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f2068)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffff8000106f2068-ffff8000106f21e8: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088cac8)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
c088cac8-c088cc58: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c00000000086fcb0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
c00000000086fcb0-c00000000086feb0: pci_bus_release_bridge_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5722)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffe0004c5722-ffffffe0004c5882: pci_bus_release_bridge_resources (STB_LOCAL)
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
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff81580ca0-ffffffff81580dcb: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff81583807-ffffffff8158386e: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8156fa80-ffffffff8156fbab: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff815725e3-ffffffff8157264a: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff81580b70-ffffffff81580c9b: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff815836d3-ffffffff8158373a: pci_bus_release_bridge_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_bus_release_bridge_resources(struct pci_bus *bus, long unsigned int type, enum release_type rel_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1553
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_release_bridge_resources
```
**Symbols:**

```
ffffffff8159b020-ffffffff8159b14b: pci_bus_release_bridge_resources (STB_LOCAL)
ffffffff8159db83-ffffffff8159dbea: pci_bus_release_bridge_resources.cold (STB_LOCAL)
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
