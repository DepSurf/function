# Function: <code>bringup_nonboot_cpus</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab1b0)
Location: kernel/cpu.c:1331
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff810ab1b0-ffffffff810ab209: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6a40)
Location: kernel/cpu.c:1335
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff810a6a40-ffffffff810a6a99: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7af0)
Location: kernel/cpu.c:1439
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff810a7af0-ffffffff810a7b49: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b9550)
Location: kernel/cpu.c:1469
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff810b9550-ffffffff810b95a9: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cff80)
Location: kernel/cpu.c:1481
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff810cff80-ffffffff810cffe0: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee410)
Location: kernel/cpu.c:1505
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff810ee410-ffffffff810ee479: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff836c9ea0)
Location: kernel/cpu.c:1867
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff836c9ea0-ffffffff836c9eda: bringup_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bringup_nonboot_cpus(unsigned int setup_max_cpus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff838fab50)
Location: kernel/cpu.c:1912
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffff838fab50-ffffffff838fab8a: bringup_nonboot_cpus (STB_GLOBAL)
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
