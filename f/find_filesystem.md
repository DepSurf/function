# Function: <code>find_filesystem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8122b070)
Location: fs/filesystems.c:46
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
```
**Symbols:**

```
ffffffff8122b070-ffffffff8122b0da: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812537d0)
Location: fs/filesystems.c:46
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
```
**Symbols:**

```
ffffffff812537d0-ffffffff81253832: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81266a20)
Location: fs/filesystems.c:46
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
```
**Symbols:**

```
ffffffff81266a20-ffffffff81266a82: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81274220)
Location: fs/filesystems.c:47
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff81274220-ffffffff81274282: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81296b20)
Location: fs/filesystems.c:48
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff81296b20-ffffffff81296b82: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812bcd30)
Location: fs/filesystems.c:48
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff812bcd30-ffffffff812bcd92: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812d1ff0)
Location: fs/filesystems.c:48
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff812d1ff0-ffffffff812d2052: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812ef040)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff812ef040-ffffffff812ef0ab: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81300b00)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff81300b00-ffffffff81300b6b: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81339f82)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81345c92)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8134c052)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81399e92)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff8141cbe2)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814a8d72)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff814ddd42)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81510792)
Location: fs/filesystems.c:49
Inline: True
Inline callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
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
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffff8000103b2cf0)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffff8000103b2cf0-ffff8000103b2d6c: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0591d04)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
c0591d04-c0591d74: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (c0000000004ae9d0)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
c0000000004ae9d0-c0000000004aea84: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffe000276a4a)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffe000276a4a-ffffffe000276ab6: find_filesystem (STB_LOCAL)
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
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f90e0)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff812f90e0-ffffffff812f914b: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812e9d00)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff812e9d00-ffffffff812e9d6b: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff812f6ef0)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff812f6ef0-ffffffff812f6f5b: find_filesystem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file_system_type **find_filesystem(const char *name, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (ffffffff81308150)
Location: fs/filesystems.c:49
Inline: False
Direct callers:
  - fs/filesystems.c:__get_fs_type
  - fs/filesystems.c:register_filesystem
```
**Symbols:**

```
ffffffff81308150-ffffffff813081bb: find_filesystem (STB_LOCAL)
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
