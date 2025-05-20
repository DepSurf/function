# Function: <code>syscall_enter_from_user_mode_prepare</code>

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
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c38960)
Location: kernel/entry/common.c:113
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff81c38960-ffffffff81c3896d: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81c2ad60)
Location: kernel/entry/common.c:114
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff81c2ad60-ffffffff81c2ad6d: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81d492f0)
Location: kernel/entry/common.c:114
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff81d492f0-ffffffff81d492fd: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff81f187b0)
Location: kernel/entry/common.c:116
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff81f187b0-ffffffff81f187c2: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff820bfdb0)
Location: kernel/entry/common.c:118
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff820bfdb0-ffffffff820bfdca: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82141bd0)
Location: kernel/entry/common.c:118
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff82141bd0-ffffffff82141bea: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void syscall_enter_from_user_mode_prepare(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff82223a70)
Location: kernel/entry/common.c:68
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
```
**Symbols:**

```
ffffffff82223a70-ffffffff82223ab7: syscall_enter_from_user_mode_prepare (STB_GLOBAL)
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
