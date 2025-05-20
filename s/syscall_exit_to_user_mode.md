# Function: <code>syscall_exit_to_user_mode</code>

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
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c38980)
Location: kernel/entry/common.c:298
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81c38980-ffffffff81c389c4: syscall_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2ad80)
Location: kernel/entry/common.c:299
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81c2ad80-ffffffff81c2adc4: syscall_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d49310)
Location: kernel/entry/common.c:297
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81d49310-ffffffff81d49351: syscall_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f187e0)
Location: kernel/entry/common.c:291
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81f187e0-ffffffff81f1882a: syscall_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfe00)
Location: kernel/entry/common.c:293
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff820bfe00-ffffffff820bfe4d: syscall_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141c30)
Location: kernel/entry/common.c:294
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/kernel/process.c:ret_from_fork
  - arch/x86/kernel/process.c:ret_from_fork
```
**Symbols:**

```
ffffffff82141c30-ffffffff82141c82: syscall_exit_to_user_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void syscall_exit_to_user_mode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82223ad0)
Location: kernel/entry/common.c:209
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
  - arch/x86/kernel/process.c:ret_from_fork
  - arch/x86/kernel/process.c:ret_from_fork
```
**Symbols:**

```
ffffffff82223ad0-ffffffff82223d2c: syscall_exit_to_user_mode (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
