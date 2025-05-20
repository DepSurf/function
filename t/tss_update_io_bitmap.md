# Function: <code>tss_update_io_bitmap</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810051ee)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__prepare_exit_to_usermode
```
```
In arch/x86/kernel/ioport.c (ffffffff81036f98)
Location: arch/x86/include/asm/paravirt.h:310
Inline: True
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
In arch/x86/kernel/ioport.c (ffffffff81038058)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
```
```
In kernel/entry/common.c (ffffffff8113bb61)
Location: arch/x86/include/asm/paravirt.h:306
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
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
In arch/x86/kernel/ioport.c (ffffffff81039b98)
Location: arch/x86/include/asm/paravirt.h:323
Inline: True
```
```
In kernel/entry/common.c (ffffffff8113ce4b)
Location: arch/x86/include/asm/paravirt.h:323
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
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
In arch/x86/kernel/ioport.c (ffffffff8103f548)
Location: arch/x86/include/asm/paravirt.h:323
Inline: True
```
```
In kernel/entry/common.c (ffffffff8115ff68)
Location: arch/x86/include/asm/paravirt.h:323
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
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
In arch/x86/kernel/ioport.c (ffffffff81046bc5)
Location: arch/x86/include/asm/paravirt.h:329
Inline: True
```
```
In kernel/entry/common.c (ffffffff8118a466)
Location: arch/x86/include/asm/paravirt.h:329
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
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
In arch/x86/kernel/ioport.c (ffffffff81050cd5)
Location: arch/x86/include/asm/paravirt.h:329
Inline: True
```
```
In kernel/entry/common.c (ffffffff811c69e6)
Location: arch/x86/include/asm/paravirt.h:329
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
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
In arch/x86/kernel/ioport.c (ffffffff81051a05)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
```
```
In kernel/entry/common.c (ffffffff811d9606)
Location: arch/x86/include/asm/paravirt.h:331
Inline: True
Inline callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
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
In arch/x86/kernel/ioport.c (ffffffff81058c25)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
```
```
In kernel/entry/common.c (ffffffff82223f89)
Location: arch/x86/include/asm/paravirt.h:333
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
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
