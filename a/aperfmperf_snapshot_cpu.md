# Function: <code>aperfmperf_snapshot_cpu</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81041f10)
Location: arch/x86/kernel/cpu/aperfmperf.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81041f10-ffffffff81041f79: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81043e20)
Location: arch/x86/kernel/cpu/aperfmperf.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81043e20-ffffffff81043e6f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81045820)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81045820-ffffffff8104586f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81047ff0)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81047ff0-ffffffff8104803f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810488a0)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff810488a0-ffffffff810488ef: aperfmperf_snapshot_cpu (STB_LOCAL)
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104cb16)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bd00)
Location: arch/x86/kernel/cpu/aperfmperf.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff8104bd00-ffffffff8104bd6f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104d830)
Location: arch/x86/kernel/cpu/aperfmperf.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff8104d830-ffffffff8104d89f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81054f30)
Location: arch/x86/kernel/cpu/aperfmperf.c:70
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81054f30-ffffffff81054ffd: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048a10)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81048a10-ffffffff81048a5f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81037ce0)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81037ce0-ffffffff81037d2f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048850)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81048850-ffffffff8104889f: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool aperfmperf_snapshot_cpu(int cpu, ktime_t now, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81049c60)
Location: arch/x86/kernel/cpu/aperfmperf.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
**Symbols:**

```
ffffffff81049c60-ffffffff81049caf: aperfmperf_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
