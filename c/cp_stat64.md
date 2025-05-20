# Function: <code>cp_stat64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81077900)
Location: arch/x86/ia32/sys_ia32.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
```
**Symbols:**

```
ffffffff81077900-ffffffff81077b1a: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81078df0)
Location: arch/x86/ia32/sys_ia32.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
```
**Symbols:**

```
ffffffff81078df0-ffffffff81078ffb: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107cbe0)
Location: arch/x86/ia32/sys_ia32.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
```
**Symbols:**

```
ffffffff8107cbe0-ffffffff8107cdeb: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107b380)
Location: arch/x86/ia32/sys_ia32.c:70
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
```
**Symbols:**

```
ffffffff8107b380-ffffffff8107b58e: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81081a80)
Location: arch/x86/ia32/sys_ia32.c:71
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:sys32_fstatat
  - arch/x86/ia32/sys_ia32.c:sys32_fstat64
  - arch/x86/ia32/sys_ia32.c:sys32_lstat64
  - arch/x86/ia32/sys_ia32.c:sys32_stat64
```
**Symbols:**

```
ffffffff81081a80-ffffffff81081c8e: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81084dd0)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff81084dd0-ffffffff81084fde: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108baa0)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff8108baa0-ffffffff8108bd4d: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f8a0)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff8108f8a0-ffffffff8108fb4c: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81090500)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff81090500-ffffffff810906a8: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103a330)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8103a330-ffffffff8103a47d: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103ab30)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8103ab30-ffffffff8103aca3: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8103c530)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8103c530-ffffffff8103c680: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81042030)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81042030-ffffffff81042180: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81049d20)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81049d20-ffffffff81049e81: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81054f00)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81054f00-ffffffff81055063: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff81056130)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff81056130-ffffffff8105627e: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sys_ia32.c (ffffffff8105d380)
Location: arch/x86/kernel/sys_ia32.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstatat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_fstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_lstat64
  - arch/x86/kernel/sys_ia32.c:__do_compat_sys_ia32_stat64
```
**Symbols:**

```
ffffffff8105d380-ffffffff8105d4ce: cp_stat64 (STB_LOCAL)
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
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f4c0)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff8108f4c0-ffffffff8108f668: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8107dfd0)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff8107dfd0-ffffffff8107e178: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff8108f470)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff8108f470-ffffffff8108f618: cp_stat64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cp_stat64(struct stat64 *ubuf, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/ia32/sys_ia32.c (ffffffff81091850)
Location: arch/x86/ia32/sys_ia32.c:72
Inline: False
Direct callers:
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstatat
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_fstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_lstat64
  - arch/x86/ia32/sys_ia32.c:__do_compat_sys_x86_stat64
```
**Symbols:**

```
ffffffff81091850-ffffffff810919f8: cp_stat64 (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
