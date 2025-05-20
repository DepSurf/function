# Function: <code>__ia32_sys_quotactl_fd</code>

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
long int __ia32_sys_quotactl_fd(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8141ea50)
Location: kernel/sys_ni.c:102
Inline: False
```
**Symbols:**

```
ffffffff8141ea50-ffffffff8141ec85: __ia32_sys_quotactl_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_sys_quotactl_fd(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814967d0)
Location: kernel/sys_ni.c:102
Inline: False
```
**Symbols:**

```
ffffffff814967d0-ffffffff81496a1b: __ia32_sys_quotactl_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_sys_quotactl_fd(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8152a750)
Location: kernel/sys_ni.c:102
Inline: False
```
**Symbols:**

```
ffffffff8152a750-ffffffff8152a99b: __ia32_sys_quotactl_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_sys_quotactl_fd(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81562b30)
Location: kernel/sys_ni.c:70
Inline: False
```
**Symbols:**

```
ffffffff81562b30-ffffffff81562d5d: __ia32_sys_quotactl_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_sys_quotactl_fd(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81599220)
Location: kernel/sys_ni.c:68
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff81599220-ffffffff8159944d: __ia32_sys_quotactl_fd (STB_GLOBAL)
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
