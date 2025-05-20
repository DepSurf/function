# Function: <code>syscall_user_dispatch</code>

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
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113bc00)
Location: kernel/entry/syscall_user_dispatch.c:34
Inline: False
```
**Symbols:**

```
ffffffff8113bc00-ffffffff8113bd21: syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff8113cef0)
Location: kernel/entry/syscall_user_dispatch.c:34
Inline: False
```
**Symbols:**

```
ffffffff8113cef0-ffffffff8113d011: syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff81160010)
Location: kernel/entry/syscall_user_dispatch.c:34
Inline: False
```
**Symbols:**

```
ffffffff81160010-ffffffff81160145: syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff8118a4e0)
Location: kernel/entry/syscall_user_dispatch.c:34
Inline: False
```
**Symbols:**

```
ffffffff8118a4e0-ffffffff8118a61d: syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811c6a80)
Location: kernel/entry/syscall_user_dispatch.c:34
Inline: False
```
**Symbols:**

```
ffffffff811c6a80-ffffffff811c6bbd: syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811d97a0)
Location: kernel/entry/syscall_user_dispatch.c:35
Inline: False
```
**Symbols:**

```
ffffffff811d97a0-ffffffff811d98dd: syscall_user_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool syscall_user_dispatch(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/syscall_user_dispatch.c (ffffffff811ef450)
Location: kernel/entry/syscall_user_dispatch.c:35
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_trace_enter
```
**Symbols:**

```
ffffffff811ef450-ffffffff811ef58d: syscall_user_dispatch (STB_GLOBAL)
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
