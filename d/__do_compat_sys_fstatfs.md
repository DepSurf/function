# Function: <code>__do_compat_sys_fstatfs</code>

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
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d5540)
Location: fs/statfs.c:295
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff812d5540-ffffffff812d5599: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea860)
Location: fs/statfs.c:295
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff812ea860-ffffffff812ea8b9: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813092d0)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff813092d0-ffffffff8130932b: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131c340)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff8131c340-ffffffff8131c39b: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81356060)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81356060-ffffffff813560b9: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813629a0)
Location: fs/statfs.c:311
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff813629a0-ffffffff813629f9: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81369440)
Location: fs/statfs.c:314
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81369440-ffffffff81369499: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b8140)
Location: fs/statfs.c:314
Inline: False
Direct callers:
  - fs/statfs.c:__x64_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff813b8140-ffffffff813b8199: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d9f0)
Location: fs/statfs.c:314
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff8143d9f0-ffffffff8143da67: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cc330)
Location: fs/statfs.c:314
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff814cc330-ffffffff814cc3a7: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81502570)
Location: fs/statfs.c:314
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81502570-ffffffff815025e7: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff815371c0)
Location: fs/statfs.c:314
Inline: False
Direct callers:
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff815371c0-ffffffff81537237: __do_compat_sys_fstatfs (STB_LOCAL)
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
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3cd0)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__arm64_compat_sys_fstatfs
```
**Symbols:**

```
ffff8000103d3cd0-ffff8000103d3d34: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d67b0)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__se_compat_sys_fstatfs
```
**Symbols:**

```
c0000000004d67b0-c0000000004d6838: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
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
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81314920)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81314920-ffffffff8131497b: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81305530)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81305530-ffffffff8130558b: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81312710)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81312710-ffffffff8131276b: __do_compat_sys_fstatfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_fstatfs(unsigned int fd, struct compat_statfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323f50)
Location: fs/statfs.c:309
Inline: False
Direct callers:
  - fs/statfs.c:__x32_compat_sys_fstatfs
  - fs/statfs.c:__ia32_compat_sys_fstatfs
```
**Symbols:**

```
ffffffff81323f50-ffffffff81323fab: __do_compat_sys_fstatfs (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
