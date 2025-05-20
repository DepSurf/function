# Function: <code>pmc_core_dbgfs_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff817474e7)
Location: drivers/platform/x86/intel_pmc_core.c:98
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/platform/x86/intel_pmc_core.c (ffffffff8177ad45)
Location: drivers/platform/x86/intel_pmc_core.c:429
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/platform/x86/intel_pmc_core.c (ffffffff81799177)
Location: drivers/platform/x86/intel_pmc_core.c:427
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/platform/x86/intel_pmc_core.c (ffffffff82710058)
Location: drivers/platform/x86/intel_pmc_core.c:489
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/platform/x86/intel_pmc_core.c (ffffffff8273a300)
Location: drivers/platform/x86/intel_pmc_core.c:489
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
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
In drivers/platform/x86/intel_pmc_core.c (ffffffff828f4274)
Location: drivers/platform/x86/intel_pmc_core.c:685
Inline: True
Inline callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd770)
Location: drivers/platform/x86/intel_pmc_core.c:759
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff818bd770-ffffffff818bd8ec: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818f0290)
Location: drivers/platform/x86/intel_pmc_core.c:760
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff818f0290-ffffffff818f040c: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4230)
Location: drivers/platform/x86/intel_pmc_core.c:1080
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff819c4230-ffffffff819c4456: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c4590)
Location: drivers/platform/x86/intel_pmc_core.c:1092
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff819c4590-ffffffff819c47b6: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmc_core_dbgfs_register(struct pmc_dev *pmcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a8810)
Location: drivers/platform/x86/intel_pmc_core.c:1496
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff819a8810-ffffffff819a8a45: pmc_core_dbgfs_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pmc_core_dbgfs_register(struct pmc_dev *pmcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81a55c30)
Location: drivers/platform/x86/intel/pmc/core.c:1833
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81a55c30-ffffffff81a55e6b: pmc_core_dbgfs_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pmc_core_dbgfs_register(struct pmc_dev *pmcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81bc5490)
Location: drivers/platform/x86/intel/pmc/core.c:1833
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81bc5490-ffffffff81bc56cd: pmc_core_dbgfs_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmc_core_dbgfs_register(struct pmc_dev *pmcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81d6d540)
Location: drivers/platform/x86/intel/pmc/core.c:945
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81d6d540-ffffffff81d6d77d: pmc_core_dbgfs_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmc_core_dbgfs_register(struct pmc_dev *pmcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (ffffffff81ddaaa0)
Location: drivers/platform/x86/intel/pmc/core.c:1044
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81ddaaa0-ffffffff81ddace1: pmc_core_dbgfs_register (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818915c0)
Location: drivers/platform/x86/intel_pmc_core.c:760
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff818915c0-ffffffff8189173c: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8184a7d0)
Location: drivers/platform/x86/intel_pmc_core.c:760
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff8184a7d0-ffffffff8184a94c: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e50c0)
Location: drivers/platform/x86/intel_pmc_core.c:760
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff818e50c0-ffffffff818e523c: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81901d20)
Location: drivers/platform/x86/intel_pmc_core.c:760
Inline: True
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_probe
```
**Symbols:**

```
ffffffff81901d20-ffffffff81901e9c: pmc_core_dbgfs_register.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
