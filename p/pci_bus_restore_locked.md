# Function: <code>pci_bus_restore_locked</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563230)
Location: drivers/pci/pci.c:5179
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffff81563230-ffffffff8156326c: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815843f0)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffff815843f0-ffffffff8158442c: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162afa0)
Location: drivers/pci/pci.c:5339
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff8162ac30-ffffffff8162ae84: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f940)
Location: drivers/pci/pci.c:5407
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff8164e3e0-ffffffff8164e634: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816324e9)
Location: drivers/pci/pci.c:5456
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff81630ff0-ffffffff8163124f: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a27b9)
Location: drivers/pci/pci.c:5646
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff816a2370-ffffffff816a25cf: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4897)
Location: drivers/pci/pci.c:5742
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff817c4430-ffffffff817c46aa: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e17f7)
Location: drivers/pci/pci.c:5679
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff818e1380-ffffffff818e15fa: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924c37)
Location: drivers/pci/pci.c:5801
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff819247c0-ffffffff81924a3a: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d307)
Location: drivers/pci/pci.c:5911
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff8196ce90-ffffffff8196d10a: pci_bus_restore_locked (STB_LOCAL)
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
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e8770)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffff8000106e8770-ffff8000106e87c0: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0883838)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
c0883838-c0883884: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000863430)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
c000000000863430-c0000000008634a0: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bed5a)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffe0004bed5a-ffffffe0004beda6: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578910)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffff81578910-ffffffff8157894c: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567050)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffff81567050-ffffffff8156708c: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578140)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffff81578140-ffffffff8157817c: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_bus_restore_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81592600)
Location: drivers/pci/pci.c:5309
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_restore_locked
```
**Symbols:**

```
ffffffff81592600-ffffffff8159263c: pci_bus_restore_locked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
