# Function: <code>ksys_readahead</code>

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
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81200520)
Location: mm/readahead.c:589
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff81200520-ffffffff812005e6: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81212ec0)
Location: mm/readahead.c:575
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff81212ec0-ffffffff81212f5f: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812228d0)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff812228d0-ffffffff81222972: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81230380)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff81230380-ffffffff81230422: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8125d630)
Location: mm/readahead.c:635
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff8125d630-ffffffff8125d6d2: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812679e0)
Location: mm/readahead.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff812679e0-ffffffff81267a82: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8126c5f0)
Location: mm/readahead.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff8126c5f0-ffffffff8126c692: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812a9310)
Location: mm/readahead.c:613
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff812a9310-ffffffff812a93b5: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813024c0)
Location: mm/readahead.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff813024c0-ffffffff81302589: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8136cc80)
Location: mm/readahead.c:735
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff8136cc80-ffffffff8136cd49: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8139eee0)
Location: mm/readahead.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff8139eee0-ffffffff8139efa9: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff813c8b40)
Location: mm/readahead.c:719
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_readahead
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff813c8b40-ffffffff813c8c0a: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffff8000102bfc00)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_readahead
  - mm/readahead.c:__arm64_sys_readahead
```
**Symbols:**

```
ffff8000102bfc00-ffff8000102bfcc0: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c04eb6dc)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - mm/readahead.c:__se_sys_readahead
```
**Symbols:**

```
c04eb6dc-c04eb7a4: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (c000000000378cd0)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_readahead
  - mm/readahead.c:__se_sys_readahead
```
**Symbols:**

```
c000000000378cd0-c000000000378df8: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffe0001e1bc0)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - mm/readahead.c:__se_sys_readahead
```
**Symbols:**

```
ffffffe0001e1bc0-ffffffe0001e1c56: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff812289d0)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff812289d0-ffffffff81228a72: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff8121bb10)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff8121bb10-ffffffff8121bbb2: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81226770)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff81226770-ffffffff81226812: ksys_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ksys_readahead(int fd, loff_t offset, size_t count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/readahead.c (ffffffff81235aa0)
Location: mm/readahead.c:578
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_readahead
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_readahead
  - mm/readahead.c:__ia32_sys_readahead
  - mm/readahead.c:__x64_sys_readahead
```
**Symbols:**

```
ffffffff81235aa0-ffffffff81235b42: ksys_readahead (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
