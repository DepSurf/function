# Function: <code>irq_migrate_all_off_this_cpu</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff810ee6e0)
Location: kernel/irq/cpuhotplug.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff810ee6e0-ffffffff810ee94b: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff810f7120)
Location: kernel/irq/cpuhotplug.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff810f7120-ffffffff810f73f9: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff810ff7d6-ffffffff810ff827: irq_migrate_all_off_this_cpu.cold.12 (STB_LOCAL)
ffffffff810ff460-ffffffff810ff710: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff8110afd6-ffffffff8110b00d: irq_migrate_all_off_this_cpu.cold.13 (STB_LOCAL)
ffffffff8110ac40-ffffffff8110af02: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff811146a0-ffffffff811146f0: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81114300-ffffffff811145c1: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81120800-ffffffff81120850: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81120460-ffffffff81120721: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff8112cdf6-ffffffff8112ce10: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff8112cc30-ffffffff8112ccb7: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81be1ca3-ffffffff81be1cbd: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81128660-ffffffff811286e7: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81bd3d5d-ffffffff81bd3d77: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff811288c0-ffffffff81128947: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff81148e90)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81148e90-ffffffff81148f30: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff8116da00)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff8116da00-ffffffff8116daae: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811a2c20)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff811a2c20-ffffffff811a2cce: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811b4b20)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff811b4b20-ffffffff811b4bce: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811c49a0)
Location: kernel/irq/cpuhotplug.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff811c49a0-ffffffff811c4a4e: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffff8000101861f8)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:__cpu_disable
```
**Symbols:**

```
ffff8000101861f8-ffff800010186510: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (c03d5044)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:__cpu_disable
```
**Symbols:**

```
c03d5044-c03d52d0: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (c0000000001e09d0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/powerpc/kernel/smp.c:generic_cpu_disable
  - arch/powerpc/sysdev/xive/common.c:xive_smp_disable_cpu
```
**Symbols:**

```
c0000000001e09d0-c0000000001e0cf8: irq_migrate_all_off_this_cpu (STB_GLOBAL)
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
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81118de0-ffffffff81118e30: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81118a40-ffffffff81118d01: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81109e4a-ffffffff81109e9a: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81109ab0-ffffffff81109d71: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81116cd0-ffffffff81116d20: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81116930-ffffffff81116bf1: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void irq_migrate_all_off_this_cpu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:154
Inline: False
Direct callers:
  - arch/x86/kernel/irq.c:fixup_irqs
```
**Symbols:**

```
ffffffff81122347-ffffffff811223a4: irq_migrate_all_off_this_cpu.cold (STB_LOCAL)
ffffffff81121f70-ffffffff8112227c: irq_migrate_all_off_this_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
