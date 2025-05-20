# Function: <code>fd_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81241c70)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs
  - fs/statfs.c:SYSC_fstatfs64
  - fs/compat.c:C_SYSC_fstatfs
  - fs/compat.c:C_SYSC_fstatfs64
```
**Symbols:**

```
ffffffff81241c70-ffffffff81241cc8: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81269fc0)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_fstatfs
  - fs/compat.c:C_SYSC_fstatfs64
  - fs/compat.c:C_SYSC_fstatfs
```
**Symbols:**

```
ffffffff81269fc0-ffffffff8126a018: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127cf70)
Location: fs/statfs.c:95
Inline: False
Direct callers:
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_fstatfs
  - fs/compat.c:C_SYSC_fstatfs64
  - fs/compat.c:C_SYSC_fstatfs
```
**Symbols:**

```
ffffffff8127cf70-ffffffff8127cfc8: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a920)
Location: fs/statfs.c:98
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_fstatfs64
  - fs/statfs.c:C_SYSC_fstatfs
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_fstatfs
```
**Symbols:**

```
ffffffff8128a920-ffffffff8128a978: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ad640)
Location: fs/statfs.c:99
Inline: False
Direct callers:
  - fs/statfs.c:C_SYSC_fstatfs64
  - fs/statfs.c:C_SYSC_fstatfs
  - fs/statfs.c:SYSC_fstatfs64
  - fs/statfs.c:SYSC_fstatfs
```
**Symbols:**

```
ffffffff812ad640-ffffffff812ad698: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d5380)
Location: fs/statfs.c:99
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff812d5380-ffffffff812d53e3: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea6a0)
Location: fs/statfs.c:99
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff812ea6a0-ffffffff812ea703: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81309110)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81309110-ffffffff81309172: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131c180)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff8131c180-ffffffff8131c1e2: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81355e90)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81355e90-ffffffff81355f05: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813627d0)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff813627d0-ffffffff81362845: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81369270)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81369270-ffffffff813692e5: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b7f70)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff813b7f70-ffffffff813b7fe5: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143d7b0)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff8143d7b0-ffffffff8143d839: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cc080)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff814cc080-ffffffff814cc109: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff815022c0)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff815022c0-ffffffff8150234f: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81536f10)
Location: fs/statfs.c:115
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81536f10-ffffffff81536f9f: fd_statfs (STB_GLOBAL)
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
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d3b10)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffff8000103d3b10-ffff8000103d3b90: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05ade98)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:__se_sys_fstatfs64
  - fs/statfs.c:__se_sys_fstatfs
```
**Symbols:**

```
c05ade98-c05adef8: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d6570)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
c0000000004d6570-c0000000004d6628: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e374)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffe00028e374-ffffffe00028e3e8: fd_statfs (STB_GLOBAL)
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
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81314760)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81314760-ffffffff813147c2: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81305370)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81305370-ffffffff813053d2: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81312550)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81312550-ffffffff813125b2: fd_statfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fd_statfs(int fd, struct kstatfs *st);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81323d90)
Location: fs/statfs.c:113
Inline: False
Direct callers:
  - fs/statfs.c:kcompat_sys_fstatfs64
  - fs/statfs.c:__do_compat_sys_fstatfs
  - fs/statfs.c:__do_sys_fstatfs64
  - fs/statfs.c:__do_sys_fstatfs
```
**Symbols:**

```
ffffffff81323d90-ffffffff81323df2: fd_statfs (STB_GLOBAL)
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
