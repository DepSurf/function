# Function: <code>ksys_chdir</code>

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
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296280)
Location: fs/open.c:448
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff81296280-ffffffff81296348: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab070)
Location: fs/open.c:437
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812ab070-ffffffff812ab138: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7870)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812c7870-ffffffff812c793c: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9280)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812d9280-ffffffff812d934c: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f040)
Location: fs/open.c:486
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff8130f040-ffffffff8130f10c: ksys_chdir (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e608)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__arm64_sys_chdir
```
**Symbols:**

```
ffff80001037e608-ffff80001037e6d8: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568f30)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__se_sys_chdir
```
**Symbols:**

```
c0568f30-c0569010: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474160)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__se_sys_chdir
```
**Symbols:**

```
c000000000474160-c000000000474260: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe00025428c)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__se_sys_chdir
```
**Symbols:**

```
ffffffe00025428c-ffffffe00025432e: ksys_chdir (STB_GLOBAL)
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
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1860)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812d1860-ffffffff812d192c: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c24e0)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812c24e0-ffffffff812c25ac: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf670)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812cf670-ffffffff812cf73c: ksys_chdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_chdir(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0480)
Location: fs/open.c:457
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
  - fs/open.c:__ia32_sys_chdir
  - fs/open.c:__x64_sys_chdir
```
**Symbols:**

```
ffffffff812e0480-ffffffff812e054c: ksys_chdir (STB_GLOBAL)
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
