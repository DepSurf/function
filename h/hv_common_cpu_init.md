# Function: <code>hv_common_cpu_init</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:119
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
**Symbols:**

```
ffffffff81d32eda-ffffffff81d32f02: hv_common_cpu_init.cold (STB_LOCAL)
ffffffff81a610b0-ffffffff81a61188: hv_common_cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:122
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
**Symbols:**

```
ffffffff81eff323-ffffffff81eff34b: hv_common_cpu_init.cold (STB_LOCAL)
ffffffff81bd1760-ffffffff81bd184b: hv_common_cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:122
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
**Symbols:**

```
ffffffff820aa3fa-ffffffff820aa424: hv_common_cpu_init.cold (STB_LOCAL)
ffffffff81d7d280-ffffffff81d7d370: hv_common_cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:356
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
**Symbols:**

```
ffffffff8212b8f9-ffffffff8212b923: hv_common_cpu_init.cold (STB_LOCAL)
ffffffff81deb630-ffffffff81deb71c: hv_common_cpu_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_init(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:356
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_init
```
**Symbols:**

```
ffffffff8220d54a-ffffffff8220d57a: hv_common_cpu_init.cold (STB_LOCAL)
ffffffff81ea19c0-ffffffff81ea1b07: hv_common_cpu_init (STB_GLOBAL)
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
