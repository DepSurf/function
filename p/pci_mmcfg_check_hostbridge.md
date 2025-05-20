# Function: <code>pci_mmcfg_check_hostbridge</code>

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
In arch/x86/pci/mmconfig-shared.c (ffffffff81fb8edd)
Location: arch/x86/pci/mmconfig-shared.c:341
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff81fe6ab0)
Location: arch/x86/pci/mmconfig-shared.c:341
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff820252f4)
Location: arch/x86/pci/mmconfig-shared.c:341
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff821087da)
Location: arch/x86/pci/mmconfig-shared.c:341
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8271212c)
Location: arch/x86/pci/mmconfig-shared.c:342
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8273bf05)
Location: arch/x86/pci/mmconfig-shared.c:342
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff828f5f17)
Location: arch/x86/pci/mmconfig-shared.c:342
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff82911967)
Location: arch/x86/pci/mmconfig-shared.c:342
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8291b6fe)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_mmcfg_check_hostbridge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82d3130a)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff82d3130a-ffffffff82d31405: pci_mmcfg_check_hostbridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_mmcfg_check_hostbridge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff83020294)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
**Symbols:**

```
ffffffff83020294-ffffffff8302038f: pci_mmcfg_check_hostbridge (STB_LOCAL)
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8322b5bd)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff83315d49)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff834d0607)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff83f14600)
Location: arch/x86/pci/mmconfig-shared.c:344
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8373ad80)
Location: arch/x86/pci/mmconfig-shared.c:344
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8396f6cb)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8290040d)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff828f8a03)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff82915a09)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
In arch/x86/pci/mmconfig-shared.c (ffffffff8291c760)
Location: arch/x86/pci/mmconfig-shared.c:343
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmcfg_early_init
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
</ul>
