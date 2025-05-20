# Function: <code>identify_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040ad0)
Location: arch/x86/kernel/cpu/common.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
```
**Symbols:**

```
ffffffff81040ad0-ffffffff81040e98: identify_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040930)
Location: arch/x86/kernel/cpu/common.c:984
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81040930-ffffffff81040db7: identify_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040370)
Location: arch/x86/kernel/cpu/common.c:1009
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81040370-ffffffff810407e4: identify_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103e310)
Location: arch/x86/kernel/cpu/common.c:1070
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff8103e310-ffffffff8103e76f: identify_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040e90)
Location: arch/x86/kernel/cpu/common.c:1182
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81040e90-ffffffff810413ef: identify_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81042800)
Location: arch/x86/kernel/cpu/common.c:1290
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81042800-ffffffff81042d83: identify_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1296
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81043e20-ffffffff810443ac: identify_cpu (STB_LOCAL)
ffffffff81044adf-ffffffff81044af7: identify_cpu.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1398
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81046390-ffffffff8104695b: identify_cpu (STB_LOCAL)
ffffffff8104707b-ffffffff81047093: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81046af0-ffffffff810470ba: identify_cpu (STB_LOCAL)
ffffffff81047811-ffffffff81047829: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1436
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff8104ab30-ffffffff8104ae81: identify_cpu (STB_LOCAL)
ffffffff8104b58e-ffffffff8104b5a6: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1500
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81049fe0-ffffffff8104a37f: identify_cpu (STB_LOCAL)
ffffffff81bd4f5c-ffffffff81bd4f74: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1501
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff8104b890-ffffffff8104bbb8: identify_cpu (STB_LOCAL)
ffffffff81bc72f3-ffffffff81bc730b: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1536
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff810527f0-ffffffff81052e77: identify_cpu (STB_LOCAL)
ffffffff81c9aa27-ffffffff81c9aa69: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1769
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff8105e280-ffffffff8105e8ae: identify_cpu (STB_LOCAL)
ffffffff81e49eaa-ffffffff81e49eea: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1795
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff8106c830-ffffffff8106ce89: identify_cpu (STB_LOCAL)
ffffffff8205290e-ffffffff82052936: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff8106e210-ffffffff8106e83b: identify_cpu (STB_LOCAL)
ffffffff820d0dc9-ffffffff820d0df1: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1849
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff810754c0-ffffffff81075b2e: identify_cpu (STB_LOCAL)
ffffffff821ab8d8-ffffffff821ab900: identify_cpu.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct cpu_spec *identify_cpu(long unsigned int offset, unsigned int pvr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/cputable.c (c000000001347414)
Location: arch/powerpc/kernel/cputable.c:2230
Inline: False
Direct callers:
  - arch/powerpc/kernel/prom.c:early_init_dt_scan_cpus
  - arch/powerpc/kernel/setup_64.c:early_setup
```
**Symbols:**

```
c000000001347414-c0000000013475e0: identify_cpu (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81046c70-ffffffff8104723a: identify_cpu (STB_LOCAL)
ffffffff81047981-ffffffff81047999: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81035cb0-ffffffff810362b3: identify_cpu (STB_LOCAL)
ffffffff81036c81-ffffffff81036c99: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81046ab0-ffffffff8104707a: identify_cpu (STB_LOCAL)
ffffffff810477c1-ffffffff810477d9: identify_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void identify_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_secondary_cpu
  - arch/x86/kernel/cpu/common.c:identify_boot_cpu
```
**Symbols:**

```
ffffffff81047eb0-ffffffff8104847a: identify_cpu (STB_LOCAL)
ffffffff81048bd1-ffffffff81048be9: identify_cpu.cold (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int pvr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cpuinfo_x86 *c</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct cpu_spec *</code>
</li>
</ul>
</details>
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
