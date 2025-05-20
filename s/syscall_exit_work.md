# Function: <code>syscall_exit_work</code>

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
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b800)
Location: kernel/entry/common.c:232
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff8113b800-ffffffff8113b955: syscall_exit_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8113cae0)
Location: kernel/entry/common.c:233
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff8113cae0-ffffffff8113cc27: syscall_exit_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8115fc00)
Location: kernel/entry/common.c:231
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff8115fc00-ffffffff8115fd44: syscall_exit_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff8118a110)
Location: kernel/entry/common.c:225
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff8118a110-ffffffff8118a260: syscall_exit_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811c6650)
Location: kernel/entry/common.c:227
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff811c6650-ffffffff811c67a0: syscall_exit_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811d9270)
Location: kernel/entry/common.c:228
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff811d9270-ffffffff811d93c0: syscall_exit_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void syscall_exit_work(struct pt_regs *regs, long unsigned int work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811eebb0)
Location: kernel/entry/common.c:143
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_to_user_mode_prepare
```
**Symbols:**

```
ffffffff811eebb0-ffffffff811eed00: syscall_exit_work (STB_LOCAL)
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
