# Function: <code>__ia32_sys_io_pgetevents</code>

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
long int __ia32_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f32e0)
Location: fs/aio.c:1904
Inline: False
```
**Symbols:**

```
ffffffff812f32e0-ffffffff812f346b: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813082e0)
Location: fs/aio.c:2125
Inline: False
```
**Symbols:**

```
ffffffff813082e0-ffffffff81308407: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *regs);
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
ffffffff8132d050-ffffffff8132d05a: __ia32_sys_io_pgetevents.cold (STB_LOCAL)
ffffffff81329db0-ffffffff81329efe: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c9880)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff8133cc10-ffffffff8133cd5e: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81375fe0)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81375fe0-ffffffff8137612c: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81384110)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81384110-ffffffff81384138: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8138ad60)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff8138ad60-ffffffff8138ad88: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813d7ee0)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff813d7ee0-ffffffff813d804d: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81462630)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81462630-ffffffff814627bd: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814f2ca0)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff814f2ca0-ffffffff814f2e23: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81529a50)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81529a50-ffffffff81529bdb: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8155e920)
Location: kernel/sys_ni.c:48
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff8155e920-ffffffff8155eaab: __ia32_sys_io_pgetevents (STB_GLOBAL)
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
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3c00)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff813351f0-ffffffff8133533e: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b2420)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81325b80-ffffffff81325cce: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c3150)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81332cc0-ffffffff81332e0e: __ia32_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __ia32_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cb590)
Location: kernel/sys_ni.c:48
Inline: False
```
**Symbols:**

```
ffffffff81345e60-ffffffff81345fae: __ia32_sys_io_pgetevents (STB_GLOBAL)
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
