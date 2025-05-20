# Function: <code>__ia32_compat_sys_io_pgetevents</code>

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
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff812f3520)
Location: fs/aio.c:1974
Inline: False
```
**Symbols:**

```
ffffffff812f3520-ffffffff812f36a4: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813084c0)
Location: fs/aio.c:2223
Inline: False
```
**Symbols:**

```
ffffffff813084c0-ffffffff813085e6: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:2188
Inline: False
```
**Symbols:**

```
ffffffff8132d05a-ffffffff8132d064: __ia32_compat_sys_io_pgetevents.cold (STB_LOCAL)
ffffffff81329fb0-ffffffff8132a0ff: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8133ce10)
Location: fs/aio.c:2204
Inline: False
```
**Symbols:**

```
ffffffff8133ce10-ffffffff8133cf56: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813761e0)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff813761e0-ffffffff81376324: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81384360)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff81384360-ffffffff8138438a: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8138afb0)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff8138afb0-ffffffff8138afd4: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff813d8110)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff813d8110-ffffffff813d8275: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814628a0)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff814628a0-ffffffff81462a23: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814f2f30)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff814f2f30-ffffffff814f30a9: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81529ce0)
Location: kernel/sys_ni.c:50
Inline: False
```
**Symbols:**

```
ffffffff81529ce0-ffffffff81529e61: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8155ebb0)
Location: kernel/sys_ni.c:50
Inline: False
Direct callers:
  - arch/x86/entry/syscall_32.c:ia32_sys_call
```
**Symbols:**

```
ffffffff8155ebb0-ffffffff8155ed31: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
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
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813353f0)
Location: fs/aio.c:2204
Inline: False
```
**Symbols:**

```
ffffffff813353f0-ffffffff81335536: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81325d80)
Location: fs/aio.c:2204
Inline: False
```
**Symbols:**

```
ffffffff81325d80-ffffffff81325ec6: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81332ec0)
Location: fs/aio.c:2204
Inline: False
```
**Symbols:**

```
ffffffff81332ec0-ffffffff81333006: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __ia32_compat_sys_io_pgetevents(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81346060)
Location: fs/aio.c:2204
Inline: False
```
**Symbols:**

```
ffffffff81346060-ffffffff813461a6: __ia32_compat_sys_io_pgetevents (STB_GLOBAL)
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
