# Function: <code>prepare_exit_to_usermode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003bf0)
Location: arch/x86/entry/common.c:270
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_syscall_32_irqs_off
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
```
**Symbols:**

```
ffffffff81003bf0-ffffffff81003c0a: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d69)
Location: arch/x86/entry/common.c:185
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003ab0-ffffffff81003add: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d49)
Location: arch/x86/entry/common.c:177
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003a70-ffffffff81003aa1: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003bd9)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003900-ffffffff81003931: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003da1)
Location: arch/x86/entry/common.c:183
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003940-ffffffff810039c0: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100453e)
Location: arch/x86/entry/common.c:184
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81004150-ffffffff810041c9: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff8100456e)
Location: arch/x86/entry/common.c:184
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81004180-ffffffff810041f9: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004791)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81004310-ffffffff810043aa: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810047f1)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81004310-ffffffff810043aa: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81bbc670)
Location: arch/x86/entry/common.c:305
Inline: False
Direct callers:
  - arch/x86/entry/common.c:idtentry_exit_user
  - arch/x86/entry/common.c:idtentry_exit_cond_rcu
```
**Symbols:**

```
ffffffff81bbc670-ffffffff81bbc687: prepare_exit_to_usermode (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810047f1)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81004310-ffffffff810043aa: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81002e3f)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81002820-ffffffff810028cb: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810047b1)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff810042d0-ffffffff8100436a: prepare_exit_to_usermode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void prepare_exit_to_usermode(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810048f1)
Location: arch/x86/entry/common.c:181
Inline: True
Inline callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81004410-ffffffff810044aa: prepare_exit_to_usermode (STB_GLOBAL)
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
