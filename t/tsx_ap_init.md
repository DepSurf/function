# Function: <code>tsx_ap_init</code>

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
void tsx_ap_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81063e60)
Location: arch/x86/kernel/cpu/tsx.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81063e60-ffffffff81063f53: tsx_ap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tsx_ap_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81072fd0)
Location: arch/x86/kernel/cpu/tsx.c:246
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81072fd0-ffffffff810730c3: tsx_ap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tsx_ap_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff81074bb0)
Location: arch/x86/kernel/cpu/tsx.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81074bb0-ffffffff81074ca3: tsx_ap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tsx_ap_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/tsx.c (ffffffff8107c080)
Location: arch/x86/kernel/cpu/tsx.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff8107c080-ffffffff8107c173: tsx_ap_init (STB_GLOBAL)
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
