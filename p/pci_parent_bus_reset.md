# Function: <code>pci_parent_bus_reset</code>

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
In drivers/pci/pci.c (ffffffff814384c9)
Location: drivers/pci/pci.c:3555
Inline: True
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
In drivers/pci/pci.c (ffffffff8148417d)
Location: drivers/pci/pci.c:3876
Inline: True
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
In drivers/pci/pci.c (ffffffff814a58dd)
Location: drivers/pci/pci.c:3914
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af600)
Location: drivers/pci/pci.c:4032
Inline: False
```
**Symbols:**

```
ffffffff814af600-ffffffff814af67c: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eeb20)
Location: drivers/pci/pci.c:4069
Inline: False
```
**Symbols:**

```
ffffffff814eeb20-ffffffff814eeb9c: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e880)
Location: drivers/pci/pci.c:4318
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8151e880-ffffffff8151e8f4: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534660)
Location: drivers/pci/pci.c:4611
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81534660-ffffffff815346e5: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563b10)
Location: drivers/pci/pci.c:4708
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81563b10-ffffffff81563b93: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81584df0)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81584df0-ffffffff81584e73: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162ba50)
Location: drivers/pci/pci.c:4868
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8162ba50-ffffffff8162bad7: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651750)
Location: drivers/pci/pci.c:4942
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81651750-ffffffff816517d7: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816341c0)
Location: drivers/pci/pci.c:4991
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff816341c0-ffffffff81634247: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a456b)
Location: drivers/pci/pci.c:5043
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c69a7)
Location: drivers/pci/pci.c:5139
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e3da7)
Location: drivers/pci/pci.c:5076
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81927487)
Location: drivers/pci/pci.c:5198
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196fc27)
Location: drivers/pci/pci.c:5308
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reset_bus_function
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
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e94a0)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffff8000106e94a0-ffff8000106e9558: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0884420)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c0884420-c08844d4: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000864380)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c000000000864380-c000000000864468: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf866)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffe0004bf866-ffffffe0004bf8fa: pci_parent_bus_reset (STB_LOCAL)
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
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579310)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81579310-ffffffff81579393: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567a50)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81567a50-ffffffff81567ad3: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578b40)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81578b40-ffffffff81578bc3: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_parent_bus_reset(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81593000)
Location: drivers/pci/pci.c:4838
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81593000-ffffffff81593083: pci_parent_bus_reset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
