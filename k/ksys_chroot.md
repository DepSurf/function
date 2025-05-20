# Function: <code>ksys_chroot</code>

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
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81296390)
Location: fs/open.c:501
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff81296390-ffffffff81296493: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812ab180)
Location: fs/open.c:490
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812ab180-ffffffff812ab283: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c7980)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812c7980-ffffffff812c7a89: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d9390)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812d9390-ffffffff812d9499: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130f150)
Location: fs/open.c:539
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff8130f150-ffffffff8130f259: ksys_chroot (STB_GLOBAL)
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
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffff80001037e708)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__arm64_sys_chroot
```
**Symbols:**

```
ffff80001037e708-ffff80001037e814: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05690c8)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__se_sys_chroot
```
**Symbols:**

```
c05690c8-c05691ec: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000474290)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__se_sys_chroot
```
**Symbols:**

```
c000000000474290-c0000000004743e8: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000254408)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__se_sys_chroot
```
**Symbols:**

```
ffffffe000254408-ffffffe0002544da: ksys_chroot (STB_GLOBAL)
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
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812d1970)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812d1970-ffffffff812d1a79: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812c25f0)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812c25f0-ffffffff812c26f9: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812cf780)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812cf780-ffffffff812cf889: ksys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812e0590)
Location: fs/open.c:510
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
**Symbols:**

```
ffffffff812e0590-ffffffff812e0699: ksys_chroot (STB_GLOBAL)
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
