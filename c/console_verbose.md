# Function: <code>console_verbose</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031af4)
Location: include/linux/printk.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810448e2)
Location: include/linux/printk.h:58
Inline: True
```
```
In kernel/panic.c (ffffffff8118b973)
Location: include/linux/printk.h:58
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In lib/debug_locks.c (ffffffff813f87cc)
Location: include/linux/printk.h:58
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030c04)
Location: include/linux/printk.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044932)
Location: include/linux/printk.h:58
Inline: True
```
```
In kernel/panic.c (ffffffff8119e6a8)
Location: include/linux/printk.h:58
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In lib/debug_locks.c (ffffffff8143f65c)
Location: include/linux/printk.h:58
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810307e4)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810465b2)
Location: include/linux/printk.h:74
Inline: True
```
```
In kernel/panic.c (ffffffff811ae0d4)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In lib/debug_locks.c (ffffffff8145c75c)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102eab4)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046262)
Location: include/linux/printk.h:74
Inline: True
```
```
In kernel/panic.c (ffffffff81084803)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In lib/debug_locks.c (ffffffff8146198c)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030984)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049a92)
Location: include/linux/printk.h:75
Inline: True
```
```
In kernel/panic.c (ffffffff8108b2bc)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In lib/debug_locks.c (ffffffff8148d88c)
Location: include/linux/printk.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031bc2)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104ba30)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_panic
```
```
In kernel/panic.c (ffffffff8108ea36)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In lib/debug_locks.c (ffffffff814c260e)
Location: include/linux/printk.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81032eb5)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049110)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff81096d76)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff81176c61)
Location: include/linux/printk.h:75
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff814d6cbb)
Location: include/linux/printk.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81034cc5)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104cbc1)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff8109b2f2)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff81183a46)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff81502af3)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810354f5)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d561)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff810a1812)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff8118f8b6)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff81520a93)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810374d5)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810513d0)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff810a862b)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff811a414f)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In lib/debug_locks.c (ffffffff81bbfae3)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81038595)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050690)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff81bdb1e3)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff811a12af)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In lib/debug_locks.c (ffffffff81c38aa3)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - lib/debug_locks.c:debug_locks_off
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103a0d5)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810521b0)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff81bcd2d5)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff811a1f0f)
Location: include/linux/printk.h:77
Inline: True
Inline callers:
  - kernel/hung_task.c:check_hung_task
```
```
In lib/debug_locks.c (ffffffff815a7903)
Location: include/linux/printk.h:77
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void console_verbose();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811393cf)
Location: kernel/printk/printk.c:2458
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - kernel/panic.c:panic
  - kernel/hung_task.c:check_hung_task
```
**Symbols:**

```
ffffffff81cac173-ffffffff81cac187: console_verbose.cold (STB_LOCAL)
ffffffff811393c0-ffffffff811393fa: console_verbose (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void console_verbose();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115bc9f)
Location: kernel/printk/printk.c:2501
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - kernel/panic.c:panic
  - kernel/hung_task.c:check_hung_task
  - lib/debug_locks.c:debug_locks_off
```
**Symbols:**

```
ffffffff81e5c641-ffffffff81e5c655: console_verbose.cold (STB_LOCAL)
ffffffff8115bc90-ffffffff8115bcde: console_verbose (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void console_verbose();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118e6df)
Location: kernel/printk/printk.c:2591
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - kernel/panic.c:panic
  - kernel/hung_task.c:check_hung_task
  - lib/debug_locks.c:debug_locks_off
```
**Symbols:**

```
ffffffff82058909-ffffffff8205891d: console_verbose.cold (STB_LOCAL)
ffffffff8118e6d0-ffffffff8118e71e: console_verbose (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void console_verbose();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a003f)
Location: kernel/printk/printk.c:2533
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - kernel/panic.c:panic
  - kernel/hung_task.c:check_hung_task
  - lib/debug_locks.c:debug_locks_off
```
**Symbols:**

```
ffffffff820d71c7-ffffffff820d71db: console_verbose.cold (STB_LOCAL)
ffffffff811a0030-ffffffff811a007e: console_verbose (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void console_verbose();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811af03f)
Location: kernel/printk/printk.c:2525
Inline: True
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
  - kernel/panic.c:panic
  - kernel/hung_task.c:check_hung_task
  - lib/debug_locks.c:debug_locks_off
```
**Symbols:**

```
ffffffff821b2410-ffffffff821b2424: console_verbose.cold (STB_LOCAL)
ffffffff811af030-ffffffff811af07e: console_verbose (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff8000100959e4)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:arm64_serror_panic
  - arch/arm64/kernel/traps.c:handle_bad_stack
  - arch/arm64/kernel/traps.c:bad_mode
  - arch/arm64/kernel/traps.c:die
```
```
In kernel/panic.c (ffff8000100f6a0c)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffff800010206fac)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffff800010629ff0)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c0310260)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:bad_mode
  - arch/arm/kernel/traps.c:die
```
```
In kernel/panic.c (c0354a14)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (c0445d98)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (c07d12c8)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002c8fc)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:oops_begin
  - arch/powerpc/kernel/traps.c:panic_flush_kmsg_start
```
```
In kernel/panic.c (c00000000013c87c)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (c000000000283560)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (c0000000007cbe10)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/traps.c (ffffffe0000b6bc2)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/riscv/kernel/traps.c:die
```
```
In kernel/panic.c (ffffffe0000c25da)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffe000169650)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffe00045aa96)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035655)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d6cc)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff8109b132)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff81187ed6)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff81519073)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81024fa8)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c911)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff81089b6c)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff8117b016)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff81509373)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810354b5)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d511)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff8109b0e2)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff81185ca6)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff81515103)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81036495)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:oops_begin
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e951)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_panic
```
```
In kernel/panic.c (ffffffff810a2d59)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
```
In kernel/hung_task.c (ffffffff811935e5)
Location: include/linux/printk.h:74
Inline: True
Inline callers:
  - kernel/hung_task.c:watchdog
```
```
In lib/debug_locks.c (ffffffff8152e873)
Location: include/linux/printk.h:74
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
