# Function: <code>pci_set_bus_speed</code>

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
In drivers/pci/probe.c (ffffffff81431a16)
Location: drivers/pci/probe.c:609
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8147d206)
Location: drivers/pci/probe.c:612
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8149e776)
Location: drivers/pci/probe.c:614
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff814a8606)
Location: drivers/pci/probe.c:641
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff814e7636)
Location: drivers/pci/probe.c:641
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81516c89)
Location: drivers/pci/probe.c:665
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c6e9)
Location: drivers/pci/probe.c:664
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8155b098)
Location: drivers/pci/probe.c:721
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
In drivers/pci/probe.c (ffffffff8157c148)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816204c0)
Location: drivers/pci/probe.c:761
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff816204c0-ffffffff81620726: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646b60)
Location: drivers/pci/probe.c:768
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff81646b60-ffffffff81646dcc: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81629700)
Location: drivers/pci/probe.c:769
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff81629700-ffffffff8162996c: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816990e0)
Location: drivers/pci/probe.c:771
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff816990e0-ffffffff81699357: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817ba5d0)
Location: drivers/pci/probe.c:770
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff817ba5d0-ffffffff817ba885: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d5570)
Location: drivers/pci/probe.c:770
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff818d5570-ffffffff818d5825: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819187d0)
Location: drivers/pci/probe.c:771
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff819187d0-ffffffff81918a64: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_set_bus_speed(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960e40)
Location: drivers/pci/probe.c:782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_alloc_child_bus
```
**Symbols:**

```
ffffffff81960e40-ffffffff819610d4: pci_set_bus_speed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df75c)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087b3d8)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008581cc)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b772e)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570668)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155edc8)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fe98)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158a378)
Location: drivers/pci/probe.c:717
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_add_new_bus
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
