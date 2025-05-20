# Function: <code>syscall_enter_from_user_mode_work</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode_work(struct pt_regs *regs, long int syscall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b960)
Location: kernel/entry/common.c:94
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff8113b960-ffffffff8113b987: syscall_enter_from_user_mode_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode_work(struct pt_regs *regs, long int syscall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113cc30)
Location: kernel/entry/common.c:95
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff8113cc30-ffffffff8113cc57: syscall_enter_from_user_mode_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode_work(struct pt_regs *regs, long int syscall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115fd50)
Location: kernel/entry/common.c:95
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff8115fd50-ffffffff8115fd77: syscall_enter_from_user_mode_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode_work(struct pt_regs *regs, long int syscall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8118a260)
Location: kernel/entry/common.c:97
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff8118a260-ffffffff8118a29b: syscall_enter_from_user_mode_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode_work(struct pt_regs *regs, long int syscall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c67b0)
Location: kernel/entry/common.c:99
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff811c67b0-ffffffff811c67eb: syscall_enter_from_user_mode_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode_work(struct pt_regs *regs, long int syscall);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d93d0)
Location: kernel/entry/common.c:99
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff811d93d0-ffffffff811d940b: syscall_enter_from_user_mode_work (STB_GLOBAL)
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
In arch/x86/entry/common.c (ffffffff8221b65d)
Location: include/linux/entry-common.h:163
Inline: True
Inline callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
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
<b>Regular</b>
<ul>
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
