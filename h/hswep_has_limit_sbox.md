# Function: <code>hswep_has_limit_sbox</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81021360)
Location: arch/x86/events/intel/uncore_snbep.c:2865
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024fd0)
Location: arch/x86/events/intel/uncore_snbep.c:2885
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
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
In arch/x86/events/intel/uncore_snbep.c (ffffffff81028ddc)
Location: arch/x86/events/intel/uncore_snbep.c:2885
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool hswep_has_limit_sbox(unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c590)
Location: arch/x86/events/intel/uncore_snbep.c:2904
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
```
**Symbols:**

```
ffffffff8102c590-ffffffff8102c610: hswep_has_limit_sbox (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool hswep_has_limit_sbox(unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102c5e0)
Location: arch/x86/events/intel/uncore_snbep.c:2894
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
```
**Symbols:**

```
ffffffff8102c5e0-ffffffff8102c660: hswep_has_limit_sbox (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool hswep_has_limit_sbox(unsigned int device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81032740)
Location: arch/x86/events/intel/uncore_snbep.c:2902
Inline: False
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:bdx_uncore_cpu_init
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_cpu_init
```
**Symbols:**

```
ffffffff81032740-ffffffff810327c0: hswep_has_limit_sbox (STB_LOCAL)
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
