# Function: <code>do_cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084880)
Location: kernel/cpu.c:988
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff81084880-ffffffff81084922: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089810)
Location: kernel/cpu.c:946
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff81089810-ffffffff810898b2: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085cd0)
Location: kernel/cpu.c:858
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff81085cd0-ffffffff81085d72: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c9f0)
Location: kernel/cpu.c:1042
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff8108c9f0-ffffffff8108ca92: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1128
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff81090370-ffffffff8109044a: do_cpu_up (STB_LOCAL)
ffffffff8109175b-ffffffff81091774: do_cpu_up.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff81099162)
Location: kernel/cpu.c:1145
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff81099110-ffffffff810991d9: do_cpu_up (STB_LOCAL)
ffffffff81099a3b-ffffffff81099a54: do_cpu_up.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff8109d6e3)
Location: kernel/cpu.c:1157
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff8109d690-ffffffff8109d75a: do_cpu_up (STB_LOCAL)
ffffffff8109e020-ffffffff8109e039: do_cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810a3c33)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff810a3be0-ffffffff810a3c9e: do_cpu_up (STB_LOCAL)
ffffffff810a4598-ffffffff810a45b1: do_cpu_up.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9598)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffff8000100f9598-ffff8000100f9684: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c035787c)
Location: kernel/cpu.c:1172
Inline: False
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
c035787c-c0357924: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001403e0)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
c0000000001403e0-c00000000014051c: do_cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3e20)
Location: kernel/cpu.c:1172
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_up
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff8109d553)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff8109d500-ffffffff8109d5be: do_cpu_up (STB_LOCAL)
ffffffff8109deb8-ffffffff8109ded1: do_cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff8108bf73)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff8108bf20-ffffffff8108bfde: do_cpu_up (STB_LOCAL)
ffffffff8108c8d8-ffffffff8108c8f1: do_cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff8109d503)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff8109d4b0-ffffffff8109d56e: do_cpu_up (STB_LOCAL)
ffffffff8109de68-ffffffff8109de81: do_cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int do_cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810a5383)
Location: kernel/cpu.c:1172
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:cpu_up
```
**Symbols:**

```
ffffffff810a5330-ffffffff810a53ee: do_cpu_up (STB_LOCAL)
ffffffff810a5d58-ffffffff810a5d71: do_cpu_up.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
