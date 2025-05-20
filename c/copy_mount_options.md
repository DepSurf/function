# Function: <code>copy_mount_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_mount_options(const void *data, long unsigned int *where);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122e9d0)
Location: fs/namespace.c:2609
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff8122e9d0-ffffffff8122ebe3: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812571e0)
Location: fs/namespace.c:2595
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff812571e0-ffffffff8125740c: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126a680)
Location: fs/namespace.c:2714
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff8126a680-ffffffff8126a8a0: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81277e20)
Location: fs/namespace.c:2656
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff81277e20-ffffffff81278038: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129a860)
Location: fs/namespace.c:2721
Inline: False
Direct callers:
  - fs/namespace.c:SyS_mount
  - fs/compat.c:compat_SyS_mount
```
**Symbols:**

```
ffffffff8129a860-ffffffff8129aa7b: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c0920)
Location: fs/namespace.c:2752
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812c0920-ffffffff812c0b36: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d5b70)
Location: fs/namespace.c:2722
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812d5b70-ffffffff812d5d86: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f4350)
Location: fs/namespace.c:2988
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812f4350-ffffffff812f4508: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81305f00)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff81305f00-ffffffff813060b8: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133fbd0)
Location: fs/namespace.c:3084
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff8133fbd0-ffffffff8133fd30: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813465e0)
Location: fs/namespace.c:3090
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff813465e0-ffffffff8134667e: copy_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134ca00)
Location: fs/namespace.c:3123
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff8134ca00-ffffffff8134ca9e: copy_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139a880)
Location: fs/namespace.c:3197
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff8139a880-ffffffff8139a91e: copy_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141d5b0)
Location: fs/namespace.c:3240
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff8141d5b0-ffffffff8141d668: copy_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814a9990)
Location: fs/namespace.c:3345
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff814a9990-ffffffff814a9a48: copy_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814de870)
Location: fs/namespace.c:3532
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff814de870-ffffffff814de928: copy_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81511380)
Location: fs/namespace.c:3549
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount
  - fs/namespace.c:__x64_sys_mount
```
**Symbols:**

```
ffffffff81511380-ffffffff81511467: copy_mount_options (STB_LOCAL)
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
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b95c8)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__arm64_compat_sys_mount
```
**Symbols:**

```
ffff8000103b95c8-ffff8000103b96cc: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05970a0)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
```
**Symbols:**

```
c05970a0-c05971e4: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b6950)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__se_compat_sys_mount
```
**Symbols:**

```
c0000000004b6950-c0000000004b6ba8: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027b932)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
```
**Symbols:**

```
ffffffe00027b932-ffffffe00027ba1e: copy_mount_options (STB_GLOBAL)
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
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fe4e0)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812fe4e0-ffffffff812fe698: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef100)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812ef100-ffffffff812ef2b8: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc2d0)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff812fc2d0-ffffffff812fc488: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *copy_mount_options(const void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130d630)
Location: fs/namespace.c:3019
Inline: False
Direct callers:
  - fs/namespace.c:ksys_mount
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
**Symbols:**

```
ffffffff8130d630-ffffffff8130d7e8: copy_mount_options (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int *where</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
