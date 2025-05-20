# Function: <code>__x64_sys_io_pgetevents</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f39a0)
Location: fs/aio.c:1904
Inline: False
```
**Symbols:**

```
ffffffff812f39a0-ffffffff812f3b2d: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81308ae0)
Location: fs/aio.c:2125
Inline: False
```
**Symbols:**

```
ffffffff81308ae0-ffffffff81308c09: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:2086
Inline: False
```
**Symbols:**

```
ffffffff8132d06e-ffffffff8132d078: __x64_sys_io_pgetevents.cold (STB_LOCAL)
ffffffff8132a3b0-ffffffff8132a4ff: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c9860)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff8133d4b0-ffffffff8133d5ff: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81376880)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81376880-ffffffff813769cd: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813840e0)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff813840e0-ffffffff8138410b: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8138ad30)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff8138ad30-ffffffff8138ad5b: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813d8860)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff813d8860-ffffffff813d89ce: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81462d80)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81462d80-ffffffff81462f0f: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814f3430)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff814f3430-ffffffff814f35b5: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8152a200)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff8152a200-ffffffff8152a38d: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8155f0d0)
Location: kernel/sys_ni.c:48
Inline: False
Direct callers:
  - arch/x86/entry/syscall_64.c:x64_sys_call
```
**Symbols:**

```
ffffffff8155f0d0-ffffffff8155f25d: __x64_sys_io_pgetevents (STB_GLOBAL)
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
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3be0)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81335a90-ffffffff81335bdf: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b2400)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81326420-ffffffff8132656f: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3130)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81333560-ffffffff813336af: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x64_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb570)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81346700-ffffffff8134684f: __x64_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
