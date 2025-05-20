# Function: <code>force_exit_sig</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void force_exit_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cc9d0)
Location: kernel/signal.c:1675
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff810cc9d0-ffffffff810cca35: force_exit_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void force_exit_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3cb0)
Location: kernel/signal.c:1676
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff810e3cb0-ffffffff810e3d2f: force_exit_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void force_exit_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811042d0)
Location: kernel/signal.c:1677
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff811042d0-ffffffff8110434f: force_exit_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void force_exit_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110550)
Location: kernel/signal.c:1683
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81110550-ffffffff811105cf: force_exit_sig (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void force_exit_sig(int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81119ea0)
Location: kernel/signal.c:1689
Inline: False
Direct callers:
  - arch/x86/entry/vsyscall/vsyscall_64.c:emulate_vsyscall
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
  - kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch
```
**Symbols:**

```
ffffffff81119ea0-ffffffff81119f1f: force_exit_sig (STB_GLOBAL)
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
