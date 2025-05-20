# Function: <code>pmc_core_slps0_dbg_latch</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81878290)
Location: drivers/platform/x86/intel_pmc_core.c:558
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81878290-ffffffff81878303: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818bd030)
Location: drivers/platform/x86/intel_pmc_core.c:611
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff818bd030-ffffffff818bd0a3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818efb50)
Location: drivers/platform/x86/intel_pmc_core.c:612
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff818efb50-ffffffff818efbc3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3c40)
Location: drivers/platform/x86/intel_pmc_core.c:903
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819c3c40-ffffffff819c3cb3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819c3fc0)
Location: drivers/platform/x86/intel_pmc_core.c:915
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819c3fc0-ffffffff819c4033: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a8540)
Location: drivers/platform/x86/intel_pmc_core.c:1091
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819a8540-ffffffff819a85b3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1391
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81a56be0-ffffffff81a56c66: pmc_core_slps0_dbg_latch (STB_LOCAL)
ffffffff81d30e92-ffffffff81d30ea7: pmc_core_slps0_dbg_latch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1391
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81bc6360-ffffffff81bc63f1: pmc_core_slps0_dbg_latch (STB_LOCAL)
ffffffff81efd2a9-ffffffff81efd2be: pmc_core_slps0_dbg_latch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:499
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81d6e4c0-ffffffff81d6e551: pmc_core_slps0_dbg_latch (STB_LOCAL)
ffffffff820aa08d-ffffffff820aa0a2: pmc_core_slps0_dbg_latch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:547
Inline: False
Direct callers:
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel/pmc/core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81ddbcd0-ffffffff81ddbd61: pmc_core_slps0_dbg_latch (STB_LOCAL)
ffffffff8212b596-ffffffff8212b5ab: pmc_core_slps0_dbg_latch.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff81890e80)
Location: drivers/platform/x86/intel_pmc_core.c:612
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff81890e80-ffffffff81890ef3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff8184a140)
Location: drivers/platform/x86/intel_pmc_core.c:612
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff8184a140-ffffffff8184a1b3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff818e4980)
Location: drivers/platform/x86/intel_pmc_core.c:612
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff818e4980-ffffffff818e49f3: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pmc_core_slps0_dbg_latch(struct pmc_dev *pmcdev, bool reset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819015e0)
Location: drivers/platform/x86/intel_pmc_core.c:612
Inline: False
Direct callers:
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
  - drivers/platform/x86/intel_pmc_core.c:pmc_core_slps0_dbg_show
```
**Symbols:**

```
ffffffff819015e0-ffffffff81901653: pmc_core_slps0_dbg_latch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
