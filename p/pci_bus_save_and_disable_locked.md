# Function: <code>pci_bus_save_and_disable_locked</code>

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
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561840)
Location: drivers/pci/pci.c:5163
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffff81561840-ffffffff8156187c: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815829f0)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffff815829f0-ffffffff81582a2c: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162af12)
Location: drivers/pci/pci.c:5323
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff81629370-ffffffff816295c4: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f8b2)
Location: drivers/pci/pci.c:5391
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff8164f5d0-ffffffff8164f824: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8163245b)
Location: drivers/pci/pci.c:5440
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff816320a0-ffffffff816322ff: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a272b)
Location: drivers/pci/pci.c:5630
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff816a19c0-ffffffff816a1c1f: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4809)
Location: drivers/pci/pci.c:5726
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff817c3a90-ffffffff817c3d0a: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e1769)
Location: drivers/pci/pci.c:5663
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff818e0950-ffffffff818e0bca: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924ba9)
Location: drivers/pci/pci.c:5785
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff81923d90-ffffffff8192400a: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d279)
Location: drivers/pci/pci.c:5895
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
Direct callers:
  - drivers/pci/pci.c:__pci_reset_slot
```
**Symbols:**

```
ffffffff8196c460-ffffffff8196c6da: pci_bus_save_and_disable_locked (STB_LOCAL)
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
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6628)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffff8000106e6628-ffff8000106e6678: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881940)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
c0881940-c088198c: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008609b0)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
c0000000008609b0-c000000000860a20: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd020)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffe0004bd020-ffffffe0004bd06c: pci_bus_save_and_disable_locked (STB_LOCAL)
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
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576f10)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffff81576f10-ffffffff81576f4c: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565670)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffff81565670-ffffffff815656ac: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576740)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffff81576740-ffffffff8157677c: pci_bus_save_and_disable_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_bus_save_and_disable_locked(struct pci_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590c20)
Location: drivers/pci/pci.c:5293
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bus_save_and_disable_locked
```
**Symbols:**

```
ffffffff81590c20-ffffffff81590c5c: pci_bus_save_and_disable_locked (STB_LOCAL)
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
