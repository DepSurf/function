# Function: <code>lapic_timer_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81052ee0)
Location: arch/x86/kernel/apic/apic.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81052ee0-ffffffff81052f2a: lapic_timer_shutdown.part.2 (STB_LOCAL)
ffffffff81052f30-ffffffff81052f4b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81053167)
Location: arch/x86/kernel/apic/apic.c:480
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff810530b0-ffffffff810530fa: lapic_timer_shutdown.part.2 (STB_LOCAL)
ffffffff81053100-ffffffff8105311b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055e57)
Location: arch/x86/kernel/apic/apic.c:481
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81055da0-ffffffff81055dea: lapic_timer_shutdown.part.2 (STB_LOCAL)
ffffffff81055df0-ffffffff81055e0b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81055390)
Location: arch/x86/kernel/apic/apic.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:local_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81055390-ffffffff810553e5: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81059120)
Location: arch/x86/kernel/apic/apic.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81059120-ffffffff8105917e: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81a0255c)
Location: arch/x86/kernel/apic/apic.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8105c6e0-ffffffff8105c733: lapic_timer_shutdown.part.5 (STB_LOCAL)
ffffffff8105c740-ffffffff8105c75b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02604)
Location: arch/x86/kernel/apic/apic.c:481
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff81062360-ffffffff810623b3: lapic_timer_shutdown.part.6 (STB_LOCAL)
ffffffff810623c0-ffffffff810623db: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02854)
Location: arch/x86/kernel/apic/apic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff81065a20-ffffffff81065a73: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff81065a80-ffffffff81065a9b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02884)
Location: arch/x86/kernel/apic/apic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff81066050-ffffffff810660a3: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff810660b0-ffffffff810660cb: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8106e16d)
Location: arch/x86/kernel/apic/apic.c:480
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff8106c9c0-ffffffff8106ca13: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff8106ca20-ffffffff8106ca3b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81bd6ec6)
Location: arch/x86/kernel/apic/apic.c:489
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff8106e170-ffffffff8106e1c3: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff8106e1d0-ffffffff8106e1eb: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81bc9080)
Location: arch/x86/kernel/apic/apic.c:489
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff8106e850-ffffffff8106e8a3: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff8106e8b0-ffffffff8106e8cb: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c9dada)
Location: arch/x86/kernel/apic/apic.c:486
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff8107a1d0-ffffffff8107a223: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff8107a230-ffffffff8107a24b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81e4cf63)
Location: arch/x86/kernel/apic/apic.c:495
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff81089260-ffffffff810892bd: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff810892c0-ffffffff810892e7: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8109d681)
Location: arch/x86/kernel/apic/apic.c:496
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff8109cf80-ffffffff8109cfdd: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff8109cff0-ffffffff8109d017: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a0661)
Location: arch/x86/kernel/apic/apic.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff8109fea0-ffffffff8109fefd: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff8109ff10-ffffffff8109ff37: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff810a81a0)
Location: arch/x86/kernel/apic/apic.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:__sysvec_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff810a7f40-ffffffff810a7f8d: lapic_timer_shutdown (STB_LOCAL)
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
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02864)
Location: arch/x86/kernel/apic/apic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff81065b40-ffffffff81065b93: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff81065ba0-ffffffff81065bbb: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02714)
Location: arch/x86/kernel/apic/apic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff81055ec0-ffffffff81055f13: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff81055f20-ffffffff81055f3b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c027d4)
Location: arch/x86/kernel/apic/apic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff81065ff0-ffffffff81066043: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff81066050-ffffffff8106606b: lapic_timer_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lapic_timer_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81c02a52)
Location: arch/x86/kernel/apic/apic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
Direct callers:
  - arch/x86/kernel/apic/apic.c:smp_apic_timer_interrupt
  - arch/x86/kernel/apic/apic.c:calibrate_APIC_clock
```
**Symbols:**

```
ffffffff810675d0-ffffffff81067623: lapic_timer_shutdown.part.0 (STB_LOCAL)
ffffffff81067630-ffffffff8106764b: lapic_timer_shutdown (STB_LOCAL)
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
