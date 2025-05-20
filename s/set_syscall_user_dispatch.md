# Function: <code>set_syscall_user_dispatch</code>

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
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bd30)
Location: kernel/entry/syscall_user_dispatch.c:67
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8113bd30-ffffffff8113be0b: set_syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113d020)
Location: kernel/entry/syscall_user_dispatch.c:67
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8113d020-ffffffff8113d0dc: set_syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff81160150)
Location: kernel/entry/syscall_user_dispatch.c:71
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81160150-ffffffff8116020c: set_syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a620)
Location: kernel/entry/syscall_user_dispatch.c:71
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8118a620-ffffffff8118a6f7: set_syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6bd0)
Location: kernel/entry/syscall_user_dispatch.c:71
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811c6bd0-ffffffff811c6ca7: set_syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d98f0)
Location: kernel/entry/syscall_user_dispatch.c:121
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811d98f0-ffffffff811d9927: set_syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_syscall_user_dispatch(long unsigned int mode, long unsigned int offset, long unsigned int len, char *selector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef5a0)
Location: kernel/entry/syscall_user_dispatch.c:121
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff811ef5a0-ffffffff811ef5d7: set_syscall_user_dispatch (STB_GLOBAL)
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
