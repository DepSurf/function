# Function: <code>exit_to_user_mode_loop</code>

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
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b9a0)
Location: kernel/entry/common.c:150
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff8113b9a0-ffffffff8113baf8: exit_to_user_mode_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113cc70)
Location: kernel/entry/common.c:151
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff8113cc70-ffffffff8113cdc2: exit_to_user_mode_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115fd90)
Location: kernel/entry/common.c:151
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff8115fd90-ffffffff8115fee2: exit_to_user_mode_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8118a2b0)
Location: kernel/entry/common.c:145
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff8118a2b0-ffffffff8118a3d2: exit_to_user_mode_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c6820)
Location: kernel/entry/common.c:147
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff811c6820-ffffffff811c6946: exit_to_user_mode_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d9440)
Location: kernel/entry/common.c:147
Inline: False
Direct callers:
  - kernel/entry/common.c:exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff811d9440-ffffffff811d9566: exit_to_user_mode_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int exit_to_user_mode_loop(struct pt_regs *regs, long unsigned int ti_work);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811eef90)
Location: kernel/entry/common.c:84
Inline: True
Inline callers:
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff811eef90-ffffffff811ef0fb: exit_to_user_mode_loop (STB_GLOBAL)
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
