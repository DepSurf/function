# Function: <code>timespec64_trunc</code>

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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8be0)
Location: fs/inode.c:2115
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
```
**Symbols:**

```
ffffffff812b8be0-ffffffff812b8c49: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cdd30)
Location: fs/inode.c:2122
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff812cdd30-ffffffff812cdd99: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eab60)
Location: fs/inode.c:2154
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff812eab60-ffffffff812eabce: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc5f0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff812fc5f0-ffffffff812fc65e: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103abfe0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffff8000103abfe0-ffff8000103ac09c: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c6d8)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
c058c6d8-c058c780: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a74e0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
c0000000004a74e0-c0000000004a75b0: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe0002715b0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffe0002715b0-ffffffe00027164a: timespec64_trunc (STB_GLOBAL)
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
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4bd0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff812f4bd0-ffffffff812f4c3e: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e57f0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff812e57f0-ffffffff812e585e: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f29e0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff812f29e0-ffffffff812f2a4e: timespec64_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timespec64 timespec64_trunc(struct timespec64 t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813040f0)
Location: fs/inode.c:2165
Inline: False
Direct callers:
  - fs/fat/misc.c:fat_truncate_time
```
**Symbols:**

```
ffffffff813040f0-ffffffff8130415e: timespec64_trunc (STB_GLOBAL)
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
