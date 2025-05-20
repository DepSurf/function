# Function: <code>sys32_fallocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys32_fallocate(int fd, int mode, unsigned int offset_lo, unsigned int offset_hi, unsigned int len_lo, unsigned int len_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81077e80)
Location: arch/x86/ia32/sys_ia32.c:225
Inline: False
```
**Symbols:**

```
ffffffff81077e80-ffffffff81077ea6: sys32_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys32_fallocate(int fd, int mode, unsigned int offset_lo, unsigned int offset_hi, unsigned int len_lo, unsigned int len_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81079360)
Location: arch/x86/ia32/sys_ia32.c:225
Inline: False
```
**Symbols:**

```
ffffffff81079360-ffffffff81079385: sys32_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys32_fallocate(int fd, int mode, unsigned int offset_lo, unsigned int offset_hi, unsigned int len_lo, unsigned int len_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107d150)
Location: arch/x86/ia32/sys_ia32.c:225
Inline: False
```
**Symbols:**

```
ffffffff8107d150-ffffffff8107d175: sys32_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys32_fallocate(int fd, int mode, unsigned int offset_lo, unsigned int offset_hi, unsigned int len_lo, unsigned int len_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b950)
Location: arch/x86/ia32/sys_ia32.c:225
Inline: False
```
**Symbols:**

```
ffffffff8107b950-ffffffff8107b975: sys32_fallocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys32_fallocate(int fd, int mode, unsigned int offset_lo, unsigned int offset_hi, unsigned int len_lo, unsigned int len_hi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81082050)
Location: arch/x86/ia32/sys_ia32.c:226
Inline: False
```
**Symbols:**

```
ffffffff81082050-ffffffff81082075: sys32_fallocate (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
