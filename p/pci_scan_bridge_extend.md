# Function: <code>pci_scan_bridge_extend</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e8140)
Location: drivers/pci/probe.c:986
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff814e8140-ffffffff814e8786: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815177a0)
Location: drivers/pci/probe.c:1057
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff815177a0-ffffffff81517d66: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152d220)
Location: drivers/pci/probe.c:1057
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8152d220-ffffffff8152d7ec: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1144
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8155b970-ffffffff8155bf70: pci_scan_bridge_extend (STB_LOCAL)
ffffffff8155d6c2-ffffffff8155d73d: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8157ca20-ffffffff8157d036: pci_scan_bridge_extend (STB_LOCAL)
ffffffff8157e736-ffffffff8157e7b1: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1194
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff81621fb0-ffffffff8162262e: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81623c4d-ffffffff81623cc8: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1213
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff81648ba0-ffffffff81649219: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81bf7965-ffffffff81bf79e0: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1256
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8162b760-ffffffff8162bddb: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81be980b-ffffffff81be9887: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1265
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8169ac30-ffffffff8169b2ab: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81ce41b1-ffffffff81ce422d: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1246
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff817bc3d0-ffffffff817bca73: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81eaabc1-ffffffff81eaac44: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d82b0)
Location: drivers/pci/probe.c:1251
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff818d82b0-ffffffff818d89c3: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191b580)
Location: drivers/pci/probe.c:1254
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8191b580-ffffffff8191bd01: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819639b0)
Location: drivers/pci/probe.c:1265
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff819639b0-ffffffff81964131: pci_scan_bridge_extend (STB_LOCAL)
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
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e0178)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffff8000106e0178-ffff8000106e0720: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087be20)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
c087be20-c087c4a4: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000858f30)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
c000000000858f30-c0000000008596d0: pci_scan_bridge_extend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b8062)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffe0004b8062-ffffffe0004b84e0: pci_scan_bridge_extend (STB_LOCAL)
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
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff81570f40-ffffffff81571556: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81572c56-ffffffff81572cd1: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8155f6a0-ffffffff8155fcb6: pci_scan_bridge_extend (STB_LOCAL)
ffffffff815613b6-ffffffff81561431: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff81570770-ffffffff81570d86: pci_scan_bridge_extend (STB_LOCAL)
ffffffff81572486-ffffffff81572501: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_scan_bridge_extend(struct pci_bus *bus, struct pci_dev *dev, int max, unsigned int available_buses, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1146
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_hp_add_bridge
  - drivers/pci/probe.c:pci_scan_child_bus_extend
  - drivers/pci/probe.c:pci_scan_child_bus_extend
```
**Symbols:**

```
ffffffff8158ac50-ffffffff8158b266: pci_scan_bridge_extend (STB_LOCAL)
ffffffff8158c966-ffffffff8158c9e1: pci_scan_bridge_extend.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
