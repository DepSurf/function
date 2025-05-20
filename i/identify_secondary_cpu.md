# Function: <code>identify_secondary_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040ea0)
Location: arch/x86/kernel/cpu/common.c:1036
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81040ea0-ffffffff81040ebb: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040dc0)
Location: arch/x86/kernel/cpu/common.c:1155
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81040dc0-ffffffff81040ddb: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810407f0)
Location: arch/x86/kernel/cpu/common.c:1178
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff810407f0-ffffffff81040863: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103e770)
Location: arch/x86/kernel/cpu/common.c:1232
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff8103e770-ffffffff8103e7e3: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810413f0)
Location: arch/x86/kernel/cpu/common.c:1341
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff810413f0-ffffffff8104146c: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1449
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff8104345f-ffffffff8104347c: identify_secondary_cpu.cold.20 (STB_LOCAL)
ffffffff81042d90-ffffffff81042dfb: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1455
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81044af7-ffffffff81044b14: identify_secondary_cpu.cold.22 (STB_LOCAL)
ffffffff810443b0-ffffffff8104441b: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1558
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81047093-ffffffff810470b0: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff81046960-ffffffff810469e0: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81047829-ffffffff81047846: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff810470e0-ffffffff81047160: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104af30)
Location: arch/x86/kernel/cpu/common.c:1600
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff8104af30-ffffffff8104af66: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104a420)
Location: arch/x86/kernel/cpu/common.c:1670
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff8104a420-ffffffff8104a456: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1671
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81bc730b-ffffffff81bc7328: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff8104bc60-ffffffff8104bce5: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1706
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81c9aa69-ffffffff81c9aa86: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff81052ff0-ffffffff81053075: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1944
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81e49eea-ffffffff81e49f07: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff8105ea30-ffffffff8105eacc: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d040)
Location: arch/x86/kernel/cpu/common.c:1970
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff8106d040-ffffffff8106d0ed: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106e9a0)
Location: arch/x86/kernel/cpu/common.c:1977
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff8106e9a0-ffffffff8106ea78: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81075c90)
Location: arch/x86/kernel/cpu/common.c:2034
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81075c90-ffffffff81075d62: identify_secondary_cpu (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81047999-ffffffff810479b6: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff81047260-ffffffff810472e0: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81036c99-ffffffff81036cb6: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff81036350-ffffffff810363d0: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff810477d9-ffffffff810477f6: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff810470a0-ffffffff81047120: identify_secondary_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void identify_secondary_cpu(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1590
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:smp_store_cpu_info
```
**Symbols:**

```
ffffffff81048be9-ffffffff81048c06: identify_secondary_cpu.cold (STB_LOCAL)
ffffffff810484a0-ffffffff81048520: identify_secondary_cpu (STB_GLOBAL)
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
