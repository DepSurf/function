# Function: <code>pci_bus_dump_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e530)
Location: drivers/pci/setup-bus.c:1576
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
```
**Symbols:**

```
ffffffff8143e530-ffffffff8143e5b9: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148a390)
Location: drivers/pci/setup-bus.c:1648
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8148a390-ffffffff8148a41a: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814abb80)
Location: drivers/pci/setup-bus.c:1649
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff814abb80-ffffffff814abc0a: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b5ec0)
Location: drivers/pci/setup-bus.c:1640
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff814b5ec0-ffffffff814b5f47: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f58c0)
Location: drivers/pci/setup-bus.c:1643
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff814f58c0-ffffffff814f5947: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815265b0)
Location: drivers/pci/setup-bus.c:1638
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff815265b0-ffffffff81526637: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153c4d0)
Location: drivers/pci/setup-bus.c:1640
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8153c4d0-ffffffff8153c557: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8156bc60-ffffffff8156bcd0: pci_bus_dump_resources (STB_LOCAL)
ffffffff8156e997-ffffffff8156e9b0: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8158cc40-ffffffff8158ccb0: pci_bus_dump_resources (STB_LOCAL)
ffffffff8158f96a-ffffffff8158f983: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1635
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff81633c20-ffffffff81633c90: pci_bus_dump_resources (STB_LOCAL)
ffffffff816374a5-ffffffff816374be: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1636
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff81658cd0-ffffffff81658d40: pci_bus_dump_resources (STB_LOCAL)
ffffffff81bf8907-ffffffff81bf8920: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1636
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8163b320-ffffffff8163b390: pci_bus_dump_resources (STB_LOCAL)
ffffffff81bea764-ffffffff81bea77d: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1636
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff816abd50-ffffffff816abdc0: pci_bus_dump_resources (STB_LOCAL)
ffffffff81ce55e6-ffffffff81ce55ff: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1636
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff817cf140-ffffffff817cf1b3: pci_bus_dump_resources (STB_LOCAL)
ffffffff81eac0ac-ffffffff81eac0ca: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818eef80)
Location: drivers/pci/setup-bus.c:1636
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff818eef80-ffffffff818ef00e: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81932450)
Location: drivers/pci/setup-bus.c:1629
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff81932450-ffffffff819324de: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197afa0)
Location: drivers/pci/setup-bus.c:1639
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8197afa0-ffffffff8197b02e: pci_bus_dump_resources (STB_LOCAL)
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
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f1df0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffff8000106f1df0-ffff8000106f1eac: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088c844)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
c088c844-c088c8ec: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c00000000086fa30)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
c00000000086fa30-c00000000086fb28: pci_bus_dump_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5524)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffe0004c5524-ffffffe0004c55c0: pci_bus_dump_resources (STB_LOCAL)
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
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff81580ac0-ffffffff81580b30: pci_bus_dump_resources (STB_LOCAL)
ffffffff815837ee-ffffffff81583807: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8156f8a0-ffffffff8156f910: pci_bus_dump_resources (STB_LOCAL)
ffffffff815725ca-ffffffff815725e3: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff81580990-ffffffff81580a00: pci_bus_dump_resources (STB_LOCAL)
ffffffff815836ba-ffffffff815836d3: pci_bus_dump_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_bus_dump_resources(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:1598
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
```
**Symbols:**

```
ffffffff8159ae40-ffffffff8159aeb0: pci_bus_dump_resources (STB_LOCAL)
ffffffff8159db6a-ffffffff8159db83: pci_bus_dump_resources.cold (STB_LOCAL)
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
