# Function: <code>freq_invariance_enable</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void freq_invariance_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81060f70)
Location: arch/x86/kernel/cpu/aperfmperf.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
```
**Symbols:**

```
ffffffff81060f70-ffffffff81060fbf: freq_invariance_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void freq_invariance_enable();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106f7e0)
Location: arch/x86/kernel/cpu/aperfmperf.c:304
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
```
**Symbols:**

```
ffffffff8106f7e0-ffffffff8106f82f: freq_invariance_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void freq_invariance_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810713e0)
Location: arch/x86/kernel/cpu/aperfmperf.c:304
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
```
**Symbols:**

```
ffffffff810713e0-ffffffff8107142f: freq_invariance_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void freq_invariance_enable();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078ba0)
Location: arch/x86/kernel/cpu/aperfmperf.c:304
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:freq_invariance_set_perf_ratio
```
**Symbols:**

```
ffffffff81078ba0-ffffffff81078bef: freq_invariance_enable (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
