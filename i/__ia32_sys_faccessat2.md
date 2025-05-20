# Function: <code>__ia32_sys_faccessat2</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130efe0)
Location: fs/open.c:475
Inline: False
```
**Symbols:**

```
ffffffff8130efe0-ffffffff8130efff: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319960)
Location: fs/open.c:475
Inline: False
```
**Symbols:**

```
ffffffff81319960-ffffffff8131997f: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131fa20)
Location: fs/open.c:476
Inline: False
```
**Symbols:**

```
ffffffff8131fa20-ffffffff8131fa3c: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136cfc0)
Location: fs/open.c:473
Inline: False
```
**Symbols:**

```
ffffffff8136cfc0-ffffffff8136cfdc: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eb2f0)
Location: fs/open.c:497
Inline: False
```
**Symbols:**

```
ffffffff813eb2f0-ffffffff813eb318: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81473580)
Location: fs/open.c:497
Inline: False
```
**Symbols:**

```
ffffffff81473580-ffffffff814735a8: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a7d70)
Location: fs/open.c:534
Inline: False
```
**Symbols:**

```
ffffffff814a7d70-ffffffff814a7d98: __ia32_sys_faccessat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_sys_faccessat2(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9020)
Location: fs/open.c:539
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff814d9020-ffffffff814d9048: __ia32_sys_faccessat2 (STB_GLOBAL)
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
