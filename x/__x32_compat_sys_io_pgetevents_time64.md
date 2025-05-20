# Function: <code>__x32_compat_sys_io_pgetevents_time64</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813089b0)
Location: fs/aio.c:2256
Inline: False
```
**Symbols:**

```
ffffffff813089b0-ffffffff81308ad8: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:2223
Inline: False
```
**Symbols:**

```
ffffffff8132d082-ffffffff8132d08c: __x32_compat_sys_io_pgetevents_time64.cold (STB_LOCAL)
ffffffff8132a650-ffffffff8132a7a0: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133d360)
Location: fs/aio.c:2239
Inline: False
```
**Symbols:**

```
ffffffff8133d360-ffffffff8133d4a7: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81376730)
Location: fs/aio.c:2246
Inline: False
```
**Symbols:**

```
ffffffff81376730-ffffffff81376875: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81384550)
Location: fs/aio.c:2244
Inline: False
```
**Symbols:**

```
ffffffff81384550-ffffffff8138457b: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138b1a0)
Location: fs/aio.c:2241
Inline: False
```
**Symbols:**

```
ffffffff8138b1a0-ffffffff8138b1c5: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81335940)
Location: fs/aio.c:2239
Inline: False
```
**Symbols:**

```
ffffffff81335940-ffffffff81335a87: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81326180)
Location: fs/aio.c:2239
Inline: False
```
**Symbols:**

```
ffffffff81326180-ffffffff813262c7: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81333410)
Location: fs/aio.c:2239
Inline: False
```
**Symbols:**

```
ffffffff81333410-ffffffff81333557: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_io_pgetevents_time64(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81346460)
Location: fs/aio.c:2239
Inline: False
```
**Symbols:**

```
ffffffff81346460-ffffffff813465a7: __x32_compat_sys_io_pgetevents_time64 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
