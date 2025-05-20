# Function: <code>cond_wakeup_cpu0</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cond_wakeup_cpu0();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106ddf7)
Location: arch/x86/kernel/smpboot.c:1668
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
**Symbols:**

```
ffffffff8106c440-ffffffff8106c466: cond_wakeup_cpu0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cond_wakeup_cpu0();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81079604)
Location: arch/x86/kernel/smpboot.c:1675
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
**Symbols:**

```
ffffffff81077050-ffffffff81077076: cond_wakeup_cpu0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cond_wakeup_cpu0();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81088494)
Location: arch/x86/kernel/smpboot.c:1740
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
**Symbols:**

```
ffffffff81085ea0-ffffffff81085ed2: cond_wakeup_cpu0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cond_wakeup_cpu0();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bf54)
Location: arch/x86/kernel/smpboot.c:1740
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:native_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
  - arch/x86/kernel/smpboot.c:hlt_play_dead
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_idle_play_dead
```
**Symbols:**

```
ffffffff81099180-ffffffff810991b2: cond_wakeup_cpu0 (STB_GLOBAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
