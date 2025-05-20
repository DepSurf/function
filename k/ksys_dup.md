# Function: <code>ksys_dup</code>

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
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bcba0)
Location: fs/file.c:928
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff812bcba0-ffffffff812bcbff: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1e60)
Location: fs/file.c:958
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff812d1e60-ffffffff812d1ebf: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812eee90)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff812eee90-ffffffff812eeefc: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81300950)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff81300950-ffffffff813009bc: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81339b70)
Location: fs/file.c:989
Inline: False
Direct callers:
  - init/main.c:console_on_rootfs
  - init/main.c:console_on_rootfs
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff81339b70-ffffffff81339bfe: ksys_dup (STB_GLOBAL)
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
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b28d0)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__arm64_sys_dup
```
**Symbols:**

```
ffff8000103b28d0-ffff8000103b2954: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0591bd0)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__se_sys_dup
```
**Symbols:**

```
c0591bd0-c0591c48: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ae7e0)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__se_sys_dup
```
**Symbols:**

```
c0000000004ae7e0-c0000000004ae898: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe00027692c)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__se_sys_dup
```
**Symbols:**

```
ffffffe00027692c-ffffffe0002769a2: ksys_dup (STB_GLOBAL)
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
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f8f30)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff812f8f30-ffffffff812f8f9c: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e9b50)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff812e9b50-ffffffff812e9bbc: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f6d40)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff812f6d40-ffffffff812f6dac: ksys_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_dup(unsigned int fildes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307fb0)
Location: fs/file.c:964
Inline: False
Direct callers:
  - init/main.c:kernel_init_freeable
  - init/main.c:kernel_init_freeable
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
```
**Symbols:**

```
ffffffff81307fb0-ffffffff8130801c: ksys_dup (STB_GLOBAL)
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
