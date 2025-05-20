# Function: <code>tsx_clear_cpuid</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tsx_clear_cpuid();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81057a80)
Location: arch/x86/kernel/cpu/tsx.c:87
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81057a80-ffffffff81057ace: tsx_clear_cpuid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tsx_clear_cpuid();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81063d20)
Location: arch/x86/kernel/cpu/tsx.c:125
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81063d20-ffffffff81063db3: tsx_clear_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tsx_clear_cpuid();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81072f50)
Location: arch/x86/kernel/cpu/tsx.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81072f50-ffffffff81072fbf: tsx_clear_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tsx_clear_cpuid();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81074b30)
Location: arch/x86/kernel/cpu/tsx.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff81074b30-ffffffff81074b9f: tsx_clear_cpuid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tsx_clear_cpuid();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8107bf50)
Location: arch/x86/kernel/cpu/tsx.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/tsx.c:tsx_ap_init
  - arch/x86/kernel/cpu/tsx.c:tsx_init
```
**Symbols:**

```
ffffffff8107bf50-ffffffff8107bfbf: tsx_clear_cpuid (STB_LOCAL)
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
