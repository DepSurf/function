# Function: <code>sys32_fadvise64_64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys32_fadvise64_64(int fd, __u32 offset_low, __u32 offset_high, __u32 len_low, __u32 len_high, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81077dd0)
Location: arch/x86/ia32/sys_ia32.c:195
Inline: False
```
**Symbols:**

```
ffffffff81077dd0-ffffffff81077df8: sys32_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys32_fadvise64_64(int fd, __u32 offset_low, __u32 offset_high, __u32 len_low, __u32 len_high, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff810792b0)
Location: arch/x86/ia32/sys_ia32.c:195
Inline: False
```
**Symbols:**

```
ffffffff810792b0-ffffffff810792d7: sys32_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys32_fadvise64_64(int fd, __u32 offset_low, __u32 offset_high, __u32 len_low, __u32 len_high, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107d0a0)
Location: arch/x86/ia32/sys_ia32.c:195
Inline: False
```
**Symbols:**

```
ffffffff8107d0a0-ffffffff8107d0c7: sys32_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys32_fadvise64_64(int fd, __u32 offset_low, __u32 offset_high, __u32 len_low, __u32 len_high, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b8a0)
Location: arch/x86/ia32/sys_ia32.c:195
Inline: False
```
**Symbols:**

```
ffffffff8107b8a0-ffffffff8107b8c7: sys32_fadvise64_64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys32_fadvise64_64(int fd, __u32 offset_low, __u32 offset_high, __u32 len_low, __u32 len_high, int advice);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81081fa0)
Location: arch/x86/ia32/sys_ia32.c:196
Inline: False
```
**Symbols:**

```
ffffffff81081fa0-ffffffff81081fc7: sys32_fadvise64_64 (STB_GLOBAL)
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
