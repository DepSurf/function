# Function: <code>ksys_sync_file_range</code>

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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812d2860)
Location: fs/sync.c:285
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff812d2860-ffffffff812d299c: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff812e7c40)
Location: fs/sync.c:285
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff812e7c40-ffffffff812e7d7c: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813065f0)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff813065f0-ffffffff81306669: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81319670)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff81319670-ffffffff813196e9: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813535de)
Location: fs/sync.c:368
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff813536c0-ffffffff81353739: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8135febe)
Location: fs/sync.c:368
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff8135ffa0-ffffffff81360019: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813669ce)
Location: fs/sync.c:367
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff81366a30-ffffffff81366aa9: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff813b551e)
Location: fs/sync.c:368
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff813b5580-ffffffff813b55f9: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8143a7be)
Location: fs/sync.c:355
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff8143a840-ffffffff8143a8d5: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814c8c4e)
Location: fs/sync.c:355
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff814c8ce0-ffffffff814c8d75: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff814fee8e)
Location: fs/sync.c:355
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff814fef20-ffffffff814fefb5: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81533abe)
Location: fs/sync.c:355
Inline: True
Inline callers:
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__ia32_sys_ia32_sync_file_range
  - arch/x86/kernel/sys_ia32.c:__x64_sys_ia32_sync_file_range
```
**Symbols:**

```
ffffffff81533b50-ffffffff81533be5: ksys_sync_file_range (STB_GLOBAL)
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffff8000103d0660)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/arm64/kernel/sys32.c:__arm64_compat_sys_aarch32_sync_file_range2
  - fs/sync.c:__arm64_sys_sync_file_range2
  - fs/sync.c:__arm64_sys_sync_file_range
```
**Symbols:**

```
ffff8000103d0660-ffff8000103d06fc: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c05aba10)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - fs/sync.c:__se_sys_sync_file_range2
  - fs/sync.c:__se_sys_sync_file_range
```
**Symbols:**

```
c05aba10-c05aba94: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (c0000000004d2ec0)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/powerpc/kernel/sys_ppc32.c:compat_sys_sync_file_range2
  - fs/sync.c:__se_sys_sync_file_range2
  - fs/sync.c:__se_sys_sync_file_range
```
**Symbols:**

```
c0000000004d2ec0-c0000000004d2fa8: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffe00028c8be)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - fs/sync.c:__se_sys_sync_file_range2
  - fs/sync.c:__se_sys_sync_file_range
```
**Symbols:**

```
ffffffe00028c8be-ffffffe00028c932: ksys_sync_file_range (STB_GLOBAL)
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
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81311c50)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff81311c50-ffffffff81311cc9: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81302860)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff81302860-ffffffff813028d9: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff8130fa40)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff8130fa40-ffffffff8130fab9: ksys_sync_file_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_sync_file_range(int fd, loff_t offset, loff_t nbytes, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sync.c (ffffffff81321240)
Location: fs/sync.c:365
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__x32_compat_sys_x86_sync_file_range
  - arch/x86/ia32/sys_ia32.c:__ia32_compat_sys_x86_sync_file_range
  - fs/sync.c:__ia32_sys_sync_file_range2
  - fs/sync.c:__x64_sys_sync_file_range2
  - fs/sync.c:__ia32_sys_sync_file_range
  - fs/sync.c:__x64_sys_sync_file_range
```
**Symbols:**

```
ffffffff81321240-ffffffff813212b9: ksys_sync_file_range (STB_GLOBAL)
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
