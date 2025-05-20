# Function: <code>wrmsr_on_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b940)
Location: arch/x86/lib/msr-smp.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
```
**Symbols:**

```
ffffffff8141b940-ffffffff8141b957: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81463b00)
Location: arch/x86/lib/msr-smp.c:139
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
```
**Symbols:**

```
ffffffff81463b00-ffffffff81463b17: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482da0)
Location: arch/x86/lib/msr-smp.c:139
Inline: False
```
**Symbols:**

```
ffffffff81482da0-ffffffff81482db7: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c500)
Location: arch/x86/lib/msr-smp.c:139
Inline: False
```
**Symbols:**

```
ffffffff8148c500-ffffffff8148c517: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c85f0)
Location: arch/x86/lib/msr-smp.c:140
Inline: False
```
**Symbols:**

```
ffffffff814c85f0-ffffffff814c8607: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f93f0)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff814f93f0-ffffffff814f9407: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150dc90)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8150dc90-ffffffff8150dca7: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c310)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8153c310-ffffffff8153c327: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155d120)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8155d120-ffffffff8155d137: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6cf0)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff815e6cf0-ffffffff815e6d7a: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160be40)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8160be40-ffffffff8160beca: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815ef120)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff815ef120-ffffffff815ef1aa: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165c230)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8165c230-ffffffff8165c2ba: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81774f30)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff81774f30-ffffffff81774fe5: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5a80)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff818a5a80-ffffffff818a5b35: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e88a0)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff818e88a0-ffffffff818e8955: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8192fd40)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8192fd40-ffffffff8192fdf5: wrmsr_on_cpus (STB_GLOBAL)
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
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81555710)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff81555710-ffffffff81555727: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815459e0)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff815459e0-ffffffff815459f7: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81551450)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff81551450-ffffffff81551467: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wrmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b2b0)
Location: arch/x86/lib/msr-smp.c:141
Inline: False
```
**Symbols:**

```
ffffffff8156b2b0-ffffffff8156b2c7: wrmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
