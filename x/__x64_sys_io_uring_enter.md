# Function: <code>__x64_sys_io_uring_enter</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81330670)
Location: fs/io_uring.c:3172
Inline: False
```
**Symbols:**

```
ffffffff81330670-ffffffff813308c3: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c98e0)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff81343ef0-ffffffff813441ad: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81389280)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff81389280-ffffffff813892ab: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8139a6c0)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff8139a6c0-ffffffff8139a6eb: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813a1b00)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff813a1b00-ffffffff813a1b24: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813f0510)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff813f0510-ffffffff813f0534: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff816d6f50)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff816d6f50-ffffffff816d6f86: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81792450)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff81792450-ffffffff81792486: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff817d30d0)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff817d30d0-ffffffff817d3106: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff818163d0)
Location: kernel/sys_ni.c:52
Inline: False
Direct callers:
  - arch/x86/entry/syscall_64.c:x64_sys_call
```
**Symbols:**

```
ffffffff818163d0-ffffffff81816406: __x64_sys_io_uring_enter (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3c60)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff8133c4d0-ffffffff8133c78d: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b2480)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff8132d1a0-ffffffff8132d45d: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c31b0)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff81339fa0-ffffffff8133a25d: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x64_sys_io_uring_enter(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb5f0)
Location: kernel/sys_ni.c:52
Inline: False
```
**Symbols:**

```
ffffffff8134d370-ffffffff8134d696: __x64_sys_io_uring_enter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs *__unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs *regs</code>
</li>
</ul>
</details>
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
