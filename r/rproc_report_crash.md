# Function: <code>rproc_report_crash</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818f54ce)
Location: drivers/remoteproc/remoteproc_core.c:2205
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff818f54ce-ffffffff818f553a: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819cb8fe)
Location: drivers/remoteproc/remoteproc_core.c:2366
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff819cb8fe-ffffffff819cb955: rproc_report_crash.cold (STB_LOCAL)
ffffffff819c9600-ffffffff819c9633: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2e474)
Location: drivers/remoteproc/remoteproc_core.c:2468
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81c2e474-ffffffff81c2e4cb: rproc_report_crash.cold (STB_LOCAL)
ffffffff819c9220-ffffffff819c9253: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81c2054e)
Location: drivers/remoteproc/remoteproc_core.c:2713
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81c2054e-ffffffff81c205a5: rproc_report_crash.cold (STB_LOCAL)
ffffffff819ae2f0-ffffffff819ae323: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d31d15)
Location: drivers/remoteproc/remoteproc_core.c:2742
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81d31d09-ffffffff81d31d2f: rproc_report_crash.cold (STB_LOCAL)
ffffffff81a5c4b0-ffffffff81a5c530: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81efe1f7)
Location: drivers/remoteproc/remoteproc_core.c:2752
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81efe1eb-ffffffff81efe21f: rproc_report_crash.cold (STB_LOCAL)
ffffffff81bcc4c0-ffffffff81bcc540: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76750)
Location: drivers/remoteproc/remoteproc_core.c:2676
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81d76750-ffffffff81d76808: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4690)
Location: drivers/remoteproc/remoteproc_core.c:2677
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81de4690-ffffffff81de4748: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9a780)
Location: drivers/remoteproc/remoteproc_core.c:2677
Inline: True
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81e9a780-ffffffff81e9a838: rproc_report_crash (STB_GLOBAL)
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
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b81740)
Location: drivers/remoteproc/remoteproc_core.c:2205
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffff800010b81740-ffff800010b817d4: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c64c80)
Location: drivers/remoteproc/remoteproc_core.c:2205
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
c0c64c80-c0c64d00: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5e3a8)
Location: drivers/remoteproc/remoteproc_core.c:2205
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
c000000000c5e3a8-c000000000c5e458: rproc_report_crash (STB_GLOBAL)
```
</details>
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
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff818967fe)
Location: drivers/remoteproc/remoteproc_core.c:2205
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff818967fe-ffffffff8189686a: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rproc_report_crash(struct rproc *rproc, enum rproc_crash_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81906f5e)
Location: drivers/remoteproc/remoteproc_core.c:2205
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_iommu_fault
  - drivers/remoteproc/remoteproc_debugfs.c:rproc_crash_write
```
**Symbols:**

```
ffffffff81906f5e-ffffffff81906fca: rproc_report_crash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
