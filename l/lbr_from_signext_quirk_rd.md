# Function: <code>lbr_from_signext_quirk_rd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u64 lbr_from_signext_quirk_rd(u64 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81011790)
Location: arch/x86/events/intel/lbr.c:290
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81011020-ffffffff81011042: lbr_from_signext_quirk_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 lbr_from_signext_quirk_rd(u64 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810118c0)
Location: arch/x86/events/intel/lbr.c:290
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
**Symbols:**

```
ffffffff81011180-ffffffff810111a2: lbr_from_signext_quirk_rd (STB_GLOBAL)
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
In arch/x86/events/intel/lbr.c (ffffffff81010066)
Location: arch/x86/events/intel/lbr.c:290
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff81010869)
Location: arch/x86/events/intel/lbr.c:294
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff8101109d)
Location: arch/x86/events/intel/lbr.c:294
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff810116fd)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff81012bc4)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff81013374)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101405f)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff81013e74)
Location: arch/x86/events/intel/lbr.c:350
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff81015034)
Location: arch/x86/events/intel/lbr.c:350
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff81016641)
Location: arch/x86/events/intel/lbr.c:350
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff81018847)
Location: arch/x86/events/intel/lbr.c:329
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff8101c663)
Location: arch/x86/events/intel/lbr.c:269
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff8101c322)
Location: arch/x86/events/intel/lbr.c:269
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff810222bb)
Location: arch/x86/events/intel/lbr.c:269
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_store_lbr
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read_64
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_save
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_save
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
  - arch/x86/events/intel/lbr.c:__intel_pmu_lbr_restore
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
In arch/x86/events/intel/lbr.c (ffffffff81013374)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff8101245e)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff81013334)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
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
In arch/x86/events/intel/lbr.c (ffffffff81013554)
Location: arch/x86/events/intel/lbr.c:299
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_sched_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
