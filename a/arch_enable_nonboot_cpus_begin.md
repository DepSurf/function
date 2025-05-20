# Function: <code>arch_enable_nonboot_cpus_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052450)
Location: arch/x86/kernel/smpboot.c:1336
Inline: False
```
**Symbols:**

```
ffffffff81052450-ffffffff81052460: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81052520)
Location: arch/x86/kernel/smpboot.c:1347
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81052520-ffffffff81052530: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054e20)
Location: arch/x86/kernel/smpboot.c:1358
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81054e20-ffffffff81054e30: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054740)
Location: arch/x86/kernel/smpboot.c:1364
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81054740-ffffffff81054750: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81058540)
Location: arch/x86/kernel/smpboot.c:1263
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81058540-ffffffff81058550: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105b1c0)
Location: arch/x86/kernel/smpboot.c:1318
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff8105b1c0-ffffffff8105b1d0: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81060e40)
Location: arch/x86/kernel/smpboot.c:1319
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81060e40-ffffffff81060e50: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064440)
Location: arch/x86/kernel/smpboot.c:1380
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81064440-ffffffff81064450: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064ac0)
Location: arch/x86/kernel/smpboot.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81064ac0-ffffffff81064ad0: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
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
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9d80)
Location: kernel/cpu.c:1273
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffff8000100f9d80-ffff8000100f9d98: arch_enable_nonboot_cpus_begin (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357fe8)
Location: kernel/cpu.c:1273
Inline: True
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
c0357fe8-c0358000: arch_enable_nonboot_cpus_begin (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140e30)
Location: kernel/cpu.c:1273
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
c000000000140e30-c000000000140e3c: arch_enable_nonboot_cpus_begin (STB_WEAK)
```
</details>
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
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810645b0)
Location: arch/x86/kernel/smpboot.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff810645b0-ffffffff810645c0: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810548a0)
Location: arch/x86/kernel/smpboot.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff810548a0-ffffffff810548b0: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064a60)
Location: arch/x86/kernel/smpboot.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81064a60-ffffffff81064a70: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_enable_nonboot_cpus_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81066040)
Location: arch/x86/kernel/smpboot.c:1375
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81066040-ffffffff81066050: arch_enable_nonboot_cpus_begin (STB_GLOBAL)
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
