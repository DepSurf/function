# Function: <code>do_clear_cpu_cap</code>

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
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810420e0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff810420e0-ffffffff810421e5: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81043fc0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81043fc0-ffffffff810440c5: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810459c0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff810459c0-ffffffff81045ac5: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:92
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff810481e0-ffffffff810482de: do_clear_cpu_cap (STB_LOCAL)
ffffffff81048304-ffffffff81048317: do_clear_cpu_cap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048a90)
Location: arch/x86/kernel/cpu/cpuid-deps.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81048a90-ffffffff81048b92: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104cbc0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff8104cbc0-ffffffff8104ccb9: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104c020)
Location: arch/x86/kernel/cpu/cpuid-deps.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff8104c020-ffffffff8104c119: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8104db60)
Location: arch/x86/kernel/cpu/cpuid-deps.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff8104db60-ffffffff8104dc59: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81055330)
Location: arch/x86/kernel/cpu/cpuid-deps.c:99
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81055330-ffffffff81055429: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81061260)
Location: arch/x86/kernel/cpu/cpuid-deps.c:102
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81061260-ffffffff8106136c: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff8106fbf0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff8106fbf0-ffffffff8106fcfc: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff810717f0)
Location: arch/x86/kernel/cpu/cpuid-deps.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff810717f0-ffffffff81071908: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81079010)
Location: arch/x86/kernel/cpu/cpuid-deps.c:106
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81079010-ffffffff81079128: do_clear_cpu_cap (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048c00)
Location: arch/x86/kernel/cpu/cpuid-deps.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81048c00-ffffffff81048d02: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81037f90)
Location: arch/x86/kernel/cpu/cpuid-deps.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81037f90-ffffffff81038092: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81048a40)
Location: arch/x86/kernel/cpu/cpuid-deps.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81048a40-ffffffff81048b42: do_clear_cpu_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_clear_cpu_cap(struct cpuinfo_x86 *c, unsigned int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cpuid-deps.c (ffffffff81049e50)
Location: arch/x86/kernel/cpu/cpuid-deps.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cpuid-deps.c:setup_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
  - arch/x86/kernel/cpu/cpuid-deps.c:do_clear_cpu_cap
```
**Symbols:**

```
ffffffff81049e50-ffffffff81049f52: do_clear_cpu_cap (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
