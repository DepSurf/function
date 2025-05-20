# Function: <code>__setup_APIC_LVTT</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052fb0)
Location: arch/x86/kernel/apic/apic.c:320
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81052fb0-ffffffff810530b3: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810531c0)
Location: arch/x86/kernel/apic/apic.c:328
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff810531c0-ffffffff810532c3: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055eb0)
Location: arch/x86/kernel/apic/apic.c:329
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81055eb0-ffffffff81055fb3: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055540)
Location: arch/x86/kernel/apic/apic.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81055540-ffffffff81055620: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81059230)
Location: arch/x86/kernel/apic/apic.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81059230-ffffffff8105931f: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (0)
Location: arch/x86/kernel/apic/apic.c:323
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff8105c780-ffffffff8105c862: __setup_APIC_LVTT (STB_LOCAL)
ffffffff8105dac2-ffffffff8105dada: __setup_APIC_LVTT.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81062448)
Location: arch/x86/kernel/apic/apic.c:329
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81062400-ffffffff810624e2: __setup_APIC_LVTT (STB_LOCAL)
ffffffff81063753-ffffffff8106376b: __setup_APIC_LVTT.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81065b08)
Location: arch/x86/kernel/apic/apic.c:330
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81065ac0-ffffffff81065ba2: __setup_APIC_LVTT (STB_LOCAL)
ffffffff81066dce-ffffffff81066de6: __setup_APIC_LVTT.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81066138)
Location: arch/x86/kernel/apic/apic.c:330
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff810660f0-ffffffff810661d2: __setup_APIC_LVTT (STB_LOCAL)
ffffffff81067443-ffffffff8106745b: __setup_APIC_LVTT.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106c3d0)
Location: arch/x86/kernel/apic/apic.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
```
**Symbols:**

```
ffffffff8106c3d0-ffffffff8106c4a5: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106db60)
Location: arch/x86/kernel/apic/apic.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
```
**Symbols:**

```
ffffffff8106db60-ffffffff8106dc35: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106e5d0)
Location: arch/x86/kernel/apic/apic.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
```
**Symbols:**

```
ffffffff8106e5d0-ffffffff8106e6a5: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81079f20)
Location: arch/x86/kernel/apic/apic.c:333
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
```
**Symbols:**

```
ffffffff81079f20-ffffffff81079ff5: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81089160)
Location: arch/x86/kernel/apic/apic.c:336
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
```
**Symbols:**

```
ffffffff81089160-ffffffff81089259: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109ce70)
Location: arch/x86/kernel/apic/apic.c:337
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff8109ce70-ffffffff8109cf69: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109fd90)
Location: arch/x86/kernel/apic/apic.c:340
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff8109fd90-ffffffff8109fe89: __setup_APIC_LVTT (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff838e077d)
Location: arch/x86/kernel/apic/apic.c:307
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_periodic
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81065c28)
Location: arch/x86/kernel/apic/apic.c:330
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81065be0-ffffffff81065cc2: __setup_APIC_LVTT (STB_LOCAL)
ffffffff81066f33-ffffffff81066f4b: __setup_APIC_LVTT.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055fa8)
Location: arch/x86/kernel/apic/apic.c:330
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81055f60-ffffffff81056042: __setup_APIC_LVTT (STB_LOCAL)
ffffffff810572a5-ffffffff810572bd: __setup_APIC_LVTT.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810660d8)
Location: arch/x86/kernel/apic/apic.c:330
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81066090-ffffffff81066172: __setup_APIC_LVTT (STB_LOCAL)
ffffffff810673e3-ffffffff810673fb: __setup_APIC_LVTT.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __setup_APIC_LVTT(unsigned int clocks, int oneshot, int irqen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810676b8)
Location: arch/x86/kernel/apic/apic.c:330
Inline: True
Direct callers:
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:lapic_timer_set_oneshot
```
**Symbols:**

```
ffffffff81067670-ffffffff81067752: __setup_APIC_LVTT (STB_LOCAL)
ffffffff810689c3-ffffffff810689db: __setup_APIC_LVTT.cold (STB_LOCAL)
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
