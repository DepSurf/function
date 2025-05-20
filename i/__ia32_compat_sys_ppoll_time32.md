# Function: <code>__ia32_compat_sys_ppoll_time32</code>

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
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e51e0)
Location: fs/select.c:1373
Inline: False
```
**Symbols:**

```
ffffffff812e51e0-ffffffff812e52b8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812f6c00)
Location: fs/select.c:1373
Inline: False
```
**Symbols:**

```
ffffffff812f6c00-ffffffff812f6cd8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8132f350)
Location: kernel/sys_ni.c:433
Inline: False
```
**Symbols:**

```
ffffffff8132f350-ffffffff8132f488: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8133ac80)
Location: kernel/sys_ni.c:434
Inline: False
```
**Symbols:**

```
ffffffff8133ac80-ffffffff8133adb8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81341150)
Location: kernel/sys_ni.c:440
Inline: False
```
**Symbols:**

```
ffffffff81341150-ffffffff81341288: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8138eb10)
Location: kernel/sys_ni.c:437
Inline: False
```
**Symbols:**

```
ffffffff8138eb10-ffffffff8138ec48: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8140fe60)
Location: kernel/sys_ni.c:440
Inline: False
```
**Symbols:**

```
ffffffff8140fe60-ffffffff8140ffc3: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8149aad0)
Location: kernel/sys_ni.c:440
Inline: False
```
**Symbols:**

```
ffffffff8149aad0-ffffffff8149ac33: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814cfb80)
Location: kernel/sys_ni.c:333
Inline: False
```
**Symbols:**

```
ffffffff814cfb80-ffffffff814cfce3: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff815024c0)
Location: kernel/sys_ni.c:352
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff815024c0-ffffffff81502623: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
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
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ef1e0)
Location: fs/select.c:1373
Inline: False
```
**Symbols:**

```
ffffffff812ef1e0-ffffffff812ef2b8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812dfe10)
Location: fs/select.c:1373
Inline: False
```
**Symbols:**

```
ffffffff812dfe10-ffffffff812dfee8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812ecff0)
Location: fs/select.c:1373
Inline: False
```
**Symbols:**

```
ffffffff812ecff0-ffffffff812ed0c8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __ia32_compat_sys_ppoll_time32(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812fdff0)
Location: fs/select.c:1373
Inline: False
```
**Symbols:**

```
ffffffff812fdff0-ffffffff812fe0c8: __ia32_compat_sys_ppoll_time32 (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
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
