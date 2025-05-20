# Function: <code>__wait_for_cpus</code>

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
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810529e0)
Location: arch/x86/kernel/cpu/microcode/core.c:523
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff810529e0-ffffffff81052a63: __wait_for_cpus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81055830-ffffffff810558a8: __wait_for_cpus (STB_LOCAL)
ffffffff81055ca7-ffffffff81055cc6: __wait_for_cpus.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81052ed0-ffffffff81052f48: __wait_for_cpus (STB_LOCAL)
ffffffff81053347-ffffffff81053366: __wait_for_cpus.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81056090-ffffffff810560fb: __wait_for_cpus (STB_LOCAL)
ffffffff81056542-ffffffff81056561: __wait_for_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff810564d0-ffffffff81056536: __wait_for_cpus (STB_LOCAL)
ffffffff81056d81-ffffffff81056da0: __wait_for_cpus.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:524
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff8105b6b0-ffffffff8105b709: __wait_for_cpus.constprop.0 (STB_LOCAL)
ffffffff8105bf31-ffffffff8105bf50: __wait_for_cpus.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:522
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff8105a100-ffffffff8105a159: __wait_for_cpus.constprop.0 (STB_LOCAL)
ffffffff81bd5ea4-ffffffff81bd5ec3: __wait_for_cpus.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:522
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff8105aaa0-ffffffff8105aaf9: __wait_for_cpus.constprop.0 (STB_LOCAL)
ffffffff81bc8250-ffffffff81bc826f: __wait_for_cpus.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:522
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81063fe0-ffffffff81064039: __wait_for_cpus.constprop.0 (STB_LOCAL)
ffffffff81c9c0cb-ffffffff81c9c0ea: __wait_for_cpus.constprop.0.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81056050-ffffffff810560b6: __wait_for_cpus (STB_LOCAL)
ffffffff81056901-ffffffff81056920: __wait_for_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81046260-ffffffff810462c6: __wait_for_cpus (STB_LOCAL)
ffffffff81046b11-ffffffff81046b30: __wait_for_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81056480-ffffffff810564e6: __wait_for_cpus (STB_LOCAL)
ffffffff81056d31-ffffffff81056d50: __wait_for_cpus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __wait_for_cpus(atomic_t *t, long long int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:529
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81057920-ffffffff81057986: __wait_for_cpus (STB_LOCAL)
ffffffff810581d1-ffffffff810581f0: __wait_for_cpus.cold (STB_LOCAL)
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
