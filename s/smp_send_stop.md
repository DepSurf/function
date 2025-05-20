# Function: <code>smp_send_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8118b9f7)
Location: arch/x86/include/asm/smp.h:81
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8119e72c)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff810605c3)
Location: arch/x86/include/asm/smp.h:68
Inline: True
```
```
In kernel/panic.c (ffffffff811ae158)
Location: arch/x86/include/asm/smp.h:68
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff8105f653)
Location: arch/x86/include/asm/smp.h:68
Inline: True
```
```
In kernel/panic.c (ffffffff81084887)
Location: arch/x86/include/asm/smp.h:68
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:crash_smp_send_stop
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
In arch/x86/kernel/crash.c (ffffffff81063666)
Location: arch/x86/include/asm/smp.h:69
Inline: True
```
```
In kernel/panic.c (ffffffff8108b340)
Location: arch/x86/include/asm/smp.h:69
Inline: True
Inline callers:
  - kernel/panic.c:panic
  - kernel/panic.c:crash_smp_send_stop
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
In arch/x86/kernel/crash.c (ffffffff81066326)
Location: arch/x86/include/asm/smp.h:69
Inline: True
```
```
In kernel/panic.c (ffffffff8108eac0)
Location: arch/x86/include/asm/smp.h:69
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff8106c326)
Location: arch/x86/include/asm/smp.h:69
Inline: True
```
```
In kernel/panic.c (ffffffff81096e1a)
Location: arch/x86/include/asm/smp.h:69
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81070326)
Location: arch/x86/include/asm/smp.h:70
Inline: True
```
```
In kernel/panic.c (ffffffff8109b396)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81071326)
Location: arch/x86/include/asm/smp.h:70
Inline: True
```
```
In kernel/panic.c (ffffffff810a18c2)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81078744)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff810a86db)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81078749)
Location: arch/x86/include/asm/smp.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff81bdb293)
Location: arch/x86/include/asm/smp.h:60
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff810795de)
Location: arch/x86/include/asm/smp.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff81bcd385)
Location: arch/x86/include/asm/smp.h:60
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff8108763e)
Location: arch/x86/include/asm/smp.h:60
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff81ca3b51)
Location: arch/x86/include/asm/smp.h:60
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810977a7)
Location: arch/x86/include/asm/smp.h:67
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff81e53324)
Location: arch/x86/include/asm/smp.h:67
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810adb99)
Location: arch/x86/include/asm/smp.h:56
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff810ea63b)
Location: arch/x86/include/asm/smp.h:56
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b0b99)
Location: arch/x86/include/asm/smp.h:58
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff810f60f1)
Location: arch/x86/include/asm/smp.h:58
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/crash.c (ffffffff810b7cde)
Location: arch/x86/include/asm/smp.h:52
Inline: True
Inline callers:
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
```
In kernel/panic.c (ffffffff810ff5c6)
Location: arch/x86/include/asm/smp.h:52
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
void smp_send_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/smp.c (ffff80001009d010)
Location: arch/arm64/kernel/smp.c:969
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:machine_restart
  - arch/arm64/kernel/process.c:machine_power_off
  - arch/arm64/kernel/process.c:machine_halt
  - kernel/panic.c:panic
  - kernel/panic.c:crash_smp_send_stop
```
**Symbols:**

```
ffff80001009d010-ffff80001009d254: smp_send_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smp_send_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp.c (c0313898)
Location: arch/arm/kernel/smp.c:708
Inline: False
Direct callers:
  - arch/arm/kernel/reboot.c:machine_restart
  - arch/arm/kernel/reboot.c:machine_power_off
  - arch/arm/kernel/reboot.c:machine_halt
  - kernel/panic.c:panic
  - kernel/panic.c:crash_smp_send_stop
```
**Symbols:**

```
c0313898-c0313aa4: smp_send_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smp_send_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/smp.c (c000000000055770)
Location: arch/powerpc/kernel/smp.c:596
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup-common.c:machine_halt
  - arch/powerpc/kernel/setup-common.c:machine_power_off
  - arch/powerpc/kernel/setup-common.c:machine_restart
  - arch/powerpc/platforms/powernv/opal.c:pnv_platform_error_reboot
  - kernel/panic.c:panic
  - kernel/panic.c:crash_smp_send_stop
```
**Symbols:**

```
c000000000055770-c00000000005579c: smp_send_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smp_send_stop();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/smp.c (ffffffe0000b8034)
Location: arch/riscv/kernel/smp.c:182
Inline: False
Direct callers:
  - kernel/panic.c:panic
  - kernel/panic.c:crash_smp_send_stop
```
**Symbols:**

```
ffffffe0000b8034-ffffffe0000b813e: smp_send_stop (STB_GLOBAL)
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
In arch/x86/kernel/crash.c (ffffffff81070326)
Location: arch/x86/include/asm/smp.h:70
Inline: True
```
```
In kernel/panic.c (ffffffff8109b1e2)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81060326)
Location: arch/x86/include/asm/smp.h:70
Inline: True
```
```
In kernel/panic.c (ffffffff81089c1c)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81070326)
Location: arch/x86/include/asm/smp.h:70
Inline: True
```
```
In kernel/panic.c (ffffffff8109b192)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
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
In arch/x86/kernel/crash.c (ffffffff81072326)
Location: arch/x86/include/asm/smp.h:70
Inline: True
```
```
In kernel/panic.c (ffffffff810a2e09)
Location: arch/x86/include/asm/smp.h:70
Inline: True
Inline callers:
  - kernel/panic.c:panic
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
