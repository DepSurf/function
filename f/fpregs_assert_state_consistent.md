# Function: <code>fpregs_assert_state_consistent</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103dcd0)
Location: arch/x86/kernel/fpu/core.c:353
Inline: True
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff8103dcd0-ffffffff8103dd14: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e490)
Location: arch/x86/kernel/fpu/core.c:353
Inline: True
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff8103e490-ffffffff8103e4d3: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810414c0)
Location: arch/x86/kernel/fpu/core.c:376
Inline: True
Direct callers:
  - arch/x86/entry/common.c:__prepare_exit_to_usermode
```
**Symbols:**

```
ffffffff810414c0-ffffffff81041503: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81041560)
Location: arch/x86/kernel/fpu/core.c:416
Inline: True
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff81041560-ffffffff810415a3: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81042f60)
Location: arch/x86/kernel/fpu/core.c:416
Inline: True
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff81042f60-ffffffff81042fa3: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810492d0)
Location: arch/x86/kernel/fpu/core.c:428
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff810492d0-ffffffff81049313: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81052720)
Location: arch/x86/kernel/fpu/core.c:765
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff81052720-ffffffff8105276f: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff810604b0)
Location: arch/x86/kernel/fpu/core.c:762
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff810604b0-ffffffff810604ff: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81061d60)
Location: arch/x86/kernel/fpu/core.c:762
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff81061d60-ffffffff81061daf: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff81068e80)
Location: arch/x86/kernel/fpu/core.c:815
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/core.c:fpregs_lock_and_load
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff81068e80-ffffffff81068ecf: fpregs_assert_state_consistent (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e610)
Location: arch/x86/kernel/fpu/core.c:353
Inline: True
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff8103e610-ffffffff8103e653: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8102de10)
Location: arch/x86/kernel/fpu/core.c:353
Inline: True
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff8102de10-ffffffff8102de53: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103e450)
Location: arch/x86/kernel/fpu/core.c:353
Inline: True
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff8103e450-ffffffff8103e493: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fpregs_assert_state_consistent();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/core.c (ffffffff8103f5e0)
Location: arch/x86/kernel/fpu/core.c:353
Inline: True
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff8103f5e0-ffffffff8103f623: fpregs_assert_state_consistent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
