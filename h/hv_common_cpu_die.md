# Function: <code>hv_common_cpu_die</code>

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
int hv_common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:149
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
**Symbols:**

```
ffffffff81d32f02-ffffffff81d32f16: hv_common_cpu_die.cold (STB_LOCAL)
ffffffff81a61190-ffffffff81a61216: hv_common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:152
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
**Symbols:**

```
ffffffff81eff34b-ffffffff81eff35f: hv_common_cpu_die.cold (STB_LOCAL)
ffffffff81bd1850-ffffffff81bd18d9: hv_common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hv_common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hv/hv_common.c (0)
Location: drivers/hv/hv_common.c:152
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
**Symbols:**

```
ffffffff820aa424-ffffffff820aa438: hv_common_cpu_die.cold (STB_LOCAL)
ffffffff81d7d380-ffffffff81d7d40d: hv_common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hv/hv_common.c (ffffffff81deb730)
Location: drivers/hv/hv_common.c:393
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
**Symbols:**

```
ffffffff81deb730-ffffffff81deb741: hv_common_cpu_die (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_common_cpu_die(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hv/hv_common.c (ffffffff81ea1b20)
Location: drivers/hv/hv_common.c:422
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_cpu_die
```
**Symbols:**

```
ffffffff81ea1b20-ffffffff81ea1b31: hv_common_cpu_die (STB_GLOBAL)
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
