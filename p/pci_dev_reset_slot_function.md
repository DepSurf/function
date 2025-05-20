# Function: <code>pci_dev_reset_slot_function</code>

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
In drivers/pci/pci.c (ffffffff81438466)
Location: drivers/pci/pci.c:3590
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
In drivers/pci/pci.c (ffffffff8148411a)
Location: drivers/pci/pci.c:3911
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
In drivers/pci/pci.c (ffffffff814a587a)
Location: drivers/pci/pci.c:3949
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab8c0)
Location: drivers/pci/pci.c:4067
Inline: False
```
**Symbols:**

```
ffffffff814ab8c0-ffffffff814ab91e: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea9d0)
Location: drivers/pci/pci.c:4104
Inline: False
```
**Symbols:**

```
ffffffff814ea9d0-ffffffff814eaa2e: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519e70)
Location: drivers/pci/pci.c:4353
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81519e70-ffffffff81519ec7: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152fc00)
Location: drivers/pci/pci.c:4644
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8152fc00-ffffffff8152fc57: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155f3e0)
Location: drivers/pci/pci.c:4741
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8155f3e0-ffffffff8155f437: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580520)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81580520-ffffffff81580577: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81625a40)
Location: drivers/pci/pci.c:4901
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81625a40-ffffffff81625a97: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651caa)
Location: drivers/pci/pci.c:4975
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8163479a)
Location: drivers/pci/pci.c:5024
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_probe_reset_function
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
In drivers/pci/pci.c (ffffffff816a4515)
Location: drivers/pci/pci.c:5076
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
In drivers/pci/pci.c (ffffffff817c6945)
Location: drivers/pci/pci.c:5172
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
In drivers/pci/pci.c (ffffffff818e3d45)
Location: drivers/pci/pci.c:5109
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
In drivers/pci/pci.c (ffffffff81927425)
Location: drivers/pci/pci.c:5231
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
In drivers/pci/pci.c (ffffffff8196fbc5)
Location: drivers/pci/pci.c:5341
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
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2fa8)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffff8000106e2fa8-ffff8000106e3038: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087ee78)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c087ee78-c087eef8: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085cd80)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c00000000085cd80-c00000000085ce08: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba8a4)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffe0004ba8a4-ffffffe0004ba912: pci_dev_reset_slot_function (STB_LOCAL)
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
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574a40)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81574a40-ffffffff81574a97: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815631a0)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815631a0-ffffffff815631f7: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574270)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81574270-ffffffff815742c7: pci_dev_reset_slot_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_dev_reset_slot_function(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158e750)
Location: drivers/pci/pci.c:4871
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8158e750-ffffffff8158e7a7: pci_dev_reset_slot_function (STB_LOCAL)
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
