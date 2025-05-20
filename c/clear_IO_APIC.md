# Function: <code>clear_IO_APIC</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056a50)
Location: arch/x86/kernel/apic/io_apic.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
```
**Symbols:**

```
ffffffff81056a50-ffffffff81056aa8: clear_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81056cd0)
Location: arch/x86/kernel/apic/io_apic.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff81056cd0-ffffffff81056d28: clear_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059a80)
Location: arch/x86/kernel/apic/io_apic.c:589
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff81059a80-ffffffff81059ad8: clear_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81059210)
Location: arch/x86/kernel/apic/io_apic.c:589
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff81059210-ffffffff81059269: clear_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105d6f0)
Location: arch/x86/kernel/apic/io_apic.c:590
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:disable_IO_APIC
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
```
**Symbols:**

```
ffffffff8105d6f0-ffffffff8105d749: clear_IO_APIC (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81060b60)
Location: arch/x86/kernel/apic/io_apic.c:591
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81060b60-ffffffff81060bb8: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81066840)
Location: arch/x86/kernel/apic/io_apic.c:591
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81066840-ffffffff81066898: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81069eb0)
Location: arch/x86/kernel/apic/io_apic.c:592
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81069eb0-ffffffff81069f08: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a850)
Location: arch/x86/kernel/apic/io_apic.c:592
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff8106a850-ffffffff8106a8a8: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81071c00)
Location: arch/x86/kernel/apic/io_apic.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81071c00-ffffffff81071c58: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810730b0)
Location: arch/x86/kernel/apic/io_apic.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff810730b0-ffffffff81073108: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81073b80)
Location: arch/x86/kernel/apic/io_apic.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81073b80-ffffffff81073bd8: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81081090)
Location: arch/x86/kernel/apic/io_apic.c:566
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81081090-ffffffff81081125: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff81090b00)
Location: arch/x86/kernel/apic/io_apic.c:567
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff81090b00-ffffffff81090bb0: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a5670)
Location: arch/x86/kernel/apic/io_apic.c:567
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff810a5670-ffffffff810a5720: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810a8820)
Location: arch/x86/kernel/apic/io_apic.c:568
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff810a8820-ffffffff810a88d6: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff810af8b0)
Location: arch/x86/kernel/apic/io_apic.c:568
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff810af8b0-ffffffff810af966: clear_IO_APIC (STB_GLOBAL)
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
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a340)
Location: arch/x86/kernel/apic/io_apic.c:592
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff8106a340-ffffffff8106a398: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8105a6a0)
Location: arch/x86/kernel/apic/io_apic.c:592
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff8105a6a0-ffffffff8105a6f8: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106a7f0)
Location: arch/x86/kernel/apic/io_apic.c:592
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff8106a7f0-ffffffff8106a848: clear_IO_APIC (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clear_IO_APIC();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8106bef0)
Location: arch/x86/kernel/apic/io_apic.c:592
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_shutdown
  - arch/x86/kernel/apic/io_apic.c:enable_IO_APIC
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec
  - arch/x86/kernel/crash.c:native_machine_crash_shutdown
```
**Symbols:**

```
ffffffff8106bef0-ffffffff8106bf48: clear_IO_APIC (STB_GLOBAL)
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
