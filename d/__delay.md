# Function: <code>__delay</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff813f64b0)
Location: arch/x86/lib/delay.c:151
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__udelay
  - arch/x86/lib/delay.c:__ndelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
```
**Symbols:**

```
ffffffff813f64b0-ffffffff813f64c1: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8143d13c)
Location: arch/x86/lib/delay.c:151
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
```
**Symbols:**

```
ffffffff8143d080-ffffffff8143d091: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8145a0bc)
Location: arch/x86/lib/delay.c:151
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
```
**Symbols:**

```
ffffffff8145a000-ffffffff8145a011: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff818fbdfe)
Location: arch/x86/lib/delay.c:158
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
```
**Symbols:**

```
ffffffff818fbd10-ffffffff818fbd21: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81982c5a)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81982b60-ffffffff81982b77: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff819df1ca)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff819df0d0-ffffffff819df0e7: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1a0fa)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__ndelay
  - arch/x86/lib/delay.c:__udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81a1a000-ffffffff81a1a017: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a89d23)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81a89cd0-ffffffff81a89ce7: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ac0fe3)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81ac0f90-ffffffff81ac0fa7: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff815fd473)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay_converge
  - init/calibrate.c:calibrate_delay_converge
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff815fd420-ffffffff815fd437: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff816221a3)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay_converge
  - init/calibrate.c:calibrate_delay_converge
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81622150-ffffffff81622167: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81605a83)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81605a30-ffffffff81605a47: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81674373)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81674320-ffffffff81674337: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8178ea53)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff8178ea00-ffffffff8178ea1f: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff8204c3d3)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff8204c370-ffffffff8204c38f: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff820cace3)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff820cac80-ffffffff820cac9f: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff821a551d)
Location: arch/x86/lib/delay.c:201
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff821a54c0-ffffffff821a54df: __delay (STB_GLOBAL)
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
void __delay(long unsigned int cycles);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/lib/delay.c (ffff800010d82798)
Location: arch/arm64/lib/delay.c:26
Inline: False
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - drivers/clk/sunxi/clk-factors.c:clk_factors_set_rate
  - arch/arm64/lib/delay.c:__ndelay
  - arch/arm64/lib/delay.c:__udelay
```
**Symbols:**

```
ffff800010d82798-ffff800010d82840: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c00000000002b538)
Location: arch/powerpc/kernel/time.c:445
Inline: True
Inline callers:
  - arch/powerpc/kernel/time.c:udelay
Direct callers:
  - arch/powerpc/xmon/xmon.c:xmon_print_symbol
  - arch/powerpc/xmon/xmon.c:show_tasks
  - arch/powerpc/xmon/xmon.c:show_pte
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_opal_msglog
  - arch/powerpc/xmon/xmon.c:dump_log_buf
  - arch/powerpc/xmon/xmon.c:dump_one_xive
  - arch/powerpc/xmon/xmon.c:mwrite
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:mread
  - arch/powerpc/xmon/xmon.c:cacheflush
  - arch/powerpc/xmon/xmon.c:prregs
  - arch/powerpc/xmon/xmon.c:show_uptime
```
**Symbols:**

```
c00000000002b4a0-c00000000002b514: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int cycles);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/riscv/lib/delay.c (ffffffe0008c3c5a)
Location: arch/riscv/lib/delay.c:72
Inline: True
Inline callers:
  - arch/riscv/lib/delay.c:ndelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
```
**Symbols:**

```
ffffffe0008c3bee-ffffffe0008c3c2a: __delay (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a5fe33)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81a5fde0-ffffffff81a5fdf7: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81a1cf03)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81a1ceb0-ffffffff81a1cec7: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81acc223)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81acc1d0-ffffffff81acc1e7: __delay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __delay(long unsigned int loops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/delay.c (ffffffff81ad870d)
Location: arch/x86/lib/delay.c:159
Inline: True
Inline callers:
  - arch/x86/lib/delay.c:__const_udelay
Direct callers:
  - init/calibrate.c:calibrate_delay
  - init/calibrate.c:calibrate_delay
  - arch/x86/kernel/apic/io_apic.c:timer_irq_works
```
**Symbols:**

```
ffffffff81ad86c0-ffffffff81ad86d7: __delay (STB_GLOBAL)
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
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cycles</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int loops</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cycles</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int loops</code>
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
