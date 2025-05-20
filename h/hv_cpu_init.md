# Function: <code>hv_cpu_init</code>

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
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81029fc0)
Location: arch/x86/hyperv/hv_init.c:98
Inline: False
```
**Symbols:**

```
ffffffff81029fc0-ffffffff81029ffe: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102ade0)
Location: arch/x86/hyperv/hv_init.c:107
Inline: False
```
**Symbols:**

```
ffffffff8102ade0-ffffffff8102aeda: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b510)
Location: arch/x86/hyperv/hv_init.c:108
Inline: False
```
**Symbols:**

```
ffffffff8102b510-ffffffff8102b60a: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d280)
Location: arch/x86/hyperv/hv_init.c:48
Inline: False
```
**Symbols:**

```
ffffffff8102d280-ffffffff8102d392: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102db90)
Location: arch/x86/hyperv/hv_init.c:62
Inline: False
```
**Symbols:**

```
ffffffff8102db90-ffffffff8102dca2: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102fe60)
Location: arch/x86/hyperv/hv_init.c:77
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff8102fe60-ffffffff8102ff72: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030a90)
Location: arch/x86/hyperv/hv_init.c:80
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81030a90-ffffffff81030ba2: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031580)
Location: arch/x86/hyperv/hv_init.c:65
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81031580-ffffffff810316c8: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:53
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81036880-ffffffff81036965: hv_cpu_init (STB_LOCAL)
ffffffff81c97e10-ffffffff81c97e25: hv_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:85
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff8103c850-ffffffff8103c9b4: hv_cpu_init (STB_LOCAL)
ffffffff81e47251-ffffffff81e47266: hv_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:77
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81045230-ffffffff810453a8: hv_cpu_init (STB_LOCAL)
ffffffff82051ec0-ffffffff82051ed5: hv_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:80
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff81045370-ffffffff810454ed: hv_cpu_init (STB_LOCAL)
ffffffff820d0335-ffffffff820d034a: hv_cpu_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (0)
Location: arch/x86/hyperv/hv_init.c:84
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_resume
```
**Symbols:**

```
ffffffff8104b9d0-ffffffff8104bbb1: hv_cpu_init (STB_LOCAL)
ffffffff821aaccc-ffffffff821aace0: hv_cpu_init.cold (STB_LOCAL)
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
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102dcf0)
Location: arch/x86/hyperv/hv_init.c:62
Inline: False
```
**Symbols:**

```
ffffffff8102dcf0-ffffffff8102de02: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8101d670)
Location: arch/x86/hyperv/hv_init.c:62
Inline: False
```
**Symbols:**

```
ffffffff8101d670-ffffffff8101d7b4: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102db50)
Location: arch/x86/hyperv/hv_init.c:62
Inline: False
```
**Symbols:**

```
ffffffff8102db50-ffffffff8102dc62: hv_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hv_cpu_init(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102e940)
Location: arch/x86/hyperv/hv_init.c:62
Inline: False
```
**Symbols:**

```
ffffffff8102e940-ffffffff8102ea52: hv_cpu_init (STB_LOCAL)
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
