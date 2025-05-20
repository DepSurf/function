# Function: <code>init_counter_refs</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81069e40)
Location: arch/x86/kernel/smpboot.c:2040
Inline: True
```
**Symbols:**

```
ffffffff81069e40-ffffffff81069e7b: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106bb10)
Location: arch/x86/kernel/smpboot.c:2077
Inline: False
```
**Symbols:**

```
ffffffff8106bb10-ffffffff8106bb4b: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106c520)
Location: arch/x86/kernel/smpboot.c:2073
Inline: False
```
**Symbols:**

```
ffffffff8106c520-ffffffff8106c55b: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81077250)
Location: arch/x86/kernel/smpboot.c:2080
Inline: False
```
**Symbols:**

```
ffffffff81077250-ffffffff8107728b: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81060fe0)
Location: arch/x86/kernel/cpu/aperfmperf.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
```
**Symbols:**

```
ffffffff81060fe0-ffffffff81061033: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8106f8f0)
Location: arch/x86/kernel/cpu/aperfmperf.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
```
**Symbols:**

```
ffffffff8106f8f0-ffffffff8106f943: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810714f0)
Location: arch/x86/kernel/cpu/aperfmperf.c:39
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
```
**Symbols:**

```
ffffffff810714f0-ffffffff81071543: init_counter_refs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void init_counter_refs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81078f8a)
Location: arch/x86/kernel/cpu/aperfmperf.c:39
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:ap_init_aperfmperf
  - arch/x86/kernel/cpu/aperfmperf.c:bp_init_aperfmperf
```
**Symbols:**

```
ffffffff81078cb0-ffffffff81078d03: init_counter_refs (STB_LOCAL)
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
