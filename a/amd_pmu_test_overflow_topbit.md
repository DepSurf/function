# Function: <code>amd_pmu_test_overflow_topbit</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_topbit(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:696
Inline: False
```
**Symbols:**

```
ffffffff8100aa30-ffffffff8100aa9a: amd_pmu_test_overflow_topbit (STB_LOCAL)
ffffffff81e44766-ffffffff81e44787: amd_pmu_test_overflow_topbit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_topbit(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:646
Inline: False
```
**Symbols:**

```
ffffffff8100c640-ffffffff8100c6aa: amd_pmu_test_overflow_topbit (STB_LOCAL)
ffffffff8205044d-ffffffff8205046e: amd_pmu_test_overflow_topbit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_topbit(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:646
Inline: False
```
**Symbols:**

```
ffffffff8100be00-ffffffff8100be6a: amd_pmu_test_overflow_topbit (STB_LOCAL)
ffffffff820ce8a2-ffffffff820ce8c3: amd_pmu_test_overflow_topbit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_topbit(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:648
Inline: False
```
**Symbols:**

```
ffffffff810115e0-ffffffff8101164a: amd_pmu_test_overflow_topbit (STB_LOCAL)
ffffffff821a90de-ffffffff821a90ff: amd_pmu_test_overflow_topbit.cold (STB_LOCAL)
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
