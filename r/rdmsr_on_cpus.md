# Function: <code>rdmsr_on_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8141b920)
Location: arch/x86/lib/msr-smp.c:125
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
```
**Symbols:**

```
ffffffff8141b920-ffffffff8141b937: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81463ae0)
Location: arch/x86/lib/msr-smp.c:125
Inline: False
Direct callers:
  - drivers/cpufreq/acpi-cpufreq.c:boost_set_msrs
```
**Symbols:**

```
ffffffff81463ae0-ffffffff81463af7: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81482d80)
Location: arch/x86/lib/msr-smp.c:125
Inline: False
```
**Symbols:**

```
ffffffff81482d80-ffffffff81482d97: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8148c4e0)
Location: arch/x86/lib/msr-smp.c:125
Inline: False
```
**Symbols:**

```
ffffffff8148c4e0-ffffffff8148c4f7: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814c85d0)
Location: arch/x86/lib/msr-smp.c:126
Inline: False
```
**Symbols:**

```
ffffffff814c85d0-ffffffff814c85e7: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff814f93d0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff814f93d0-ffffffff814f93e7: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8150dc70)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff8150dc70-ffffffff8150dc87: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8153c2f0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff8153c2f0-ffffffff8153c307: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8155d100)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff8155d100-ffffffff8155d117: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815e6a90)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff815e6a90-ffffffff815e6b1a: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8160bbe0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff8160bbe0-ffffffff8160bc6a: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815eeec0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff815eeec0-ffffffff815eef4a: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8165bfd0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff8165bfd0-ffffffff8165c05a: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81775230)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff81775230-ffffffff817752e5: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818a5de0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff818a5de0-ffffffff818a5e95: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff818e8bf0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff818e8bf0-ffffffff818e8ca5: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81930090)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff81930090-ffffffff81930145: rdmsr_on_cpus (STB_GLOBAL)
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
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815556f0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff815556f0-ffffffff81555707: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff815459c0)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff815459c0-ffffffff815459d7: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff81551430)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff81551430-ffffffff81551447: rdmsr_on_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rdmsr_on_cpus(const struct cpumask *mask, u32 msr_no, struct msr *msrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr-smp.c (ffffffff8156b290)
Location: arch/x86/lib/msr-smp.c:127
Inline: False
```
**Symbols:**

```
ffffffff8156b290-ffffffff8156b2a7: rdmsr_on_cpus (STB_GLOBAL)
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
