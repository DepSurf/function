# Function: <code>amd_pmu_lbr_reset</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/lbr.c (ffffffff8100d840)
Location: arch/x86/events/amd/lbr.c:322
Inline: False
Direct callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_sched_task
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_add
```
**Symbols:**

```
ffffffff8100d840-ffffffff8100d8ef: amd_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/lbr.c (ffffffff8100d010)
Location: arch/x86/events/amd/lbr.c:322
Inline: False
Direct callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_sched_task
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_add
```
**Symbols:**

```
ffffffff8100d010-ffffffff8100d0bf: amd_pmu_lbr_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_pmu_lbr_reset();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/lbr.c (ffffffff81012850)
Location: arch/x86/events/amd/lbr.c:322
Inline: False
Direct callers:
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_sched_task
  - arch/x86/events/amd/lbr.c:amd_pmu_lbr_add
```
**Symbols:**

```
ffffffff81012850-ffffffff810128ff: amd_pmu_lbr_reset (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
