# Function: <code>amd_pmu_test_overflow_status</code>

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
bool amd_pmu_test_overflow_status(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:705
Inline: False
```
**Symbols:**

```
ffffffff8100a9d0-ffffffff8100aa25: amd_pmu_test_overflow_status (STB_LOCAL)
ffffffff81e4474d-ffffffff81e44766: amd_pmu_test_overflow_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_status(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:655
Inline: False
```
**Symbols:**

```
ffffffff8100c5e0-ffffffff8100c625: amd_pmu_test_overflow_status (STB_LOCAL)
ffffffff82050434-ffffffff8205044d: amd_pmu_test_overflow_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_status(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:655
Inline: False
```
**Symbols:**

```
ffffffff8100bda0-ffffffff8100bde5: amd_pmu_test_overflow_status (STB_LOCAL)
ffffffff820ce889-ffffffff820ce8a2: amd_pmu_test_overflow_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool amd_pmu_test_overflow_status(int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/core.c (0)
Location: arch/x86/events/amd/core.c:657
Inline: False
```
**Symbols:**

```
ffffffff81011580-ffffffff810115c5: amd_pmu_test_overflow_status (STB_LOCAL)
ffffffff821a90c5-ffffffff821a90de: amd_pmu_test_overflow_status.cold (STB_LOCAL)
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
