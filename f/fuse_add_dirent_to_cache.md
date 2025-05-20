# Function: <code>fuse_add_dirent_to_cache</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff813e9cd2)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81415e32)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8142fd12)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8147fc70)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff8147fc70-ffffffff8147febe: fuse_add_dirent_to_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149b350)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff8149b350-ffffffff8149b59b: fuse_add_dirent_to_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814a0560)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff814a0560-ffffffff814a07ab: fuse_add_dirent_to_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff814f8420-ffffffff814f8679: fuse_add_dirent_to_cache (STB_LOCAL)
ffffffff81cd2348-ffffffff81cd2365: fuse_add_dirent_to_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff815887e0-ffffffff81588a3f: fuse_add_dirent_to_cache (STB_LOCAL)
ffffffff81e8547e-ffffffff81e85499: fuse_add_dirent_to_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff8162eca0-ffffffff8162ef03: fuse_add_dirent_to_cache (STB_LOCAL)
ffffffff82072928-ffffffff82072943: fuse_add_dirent_to_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff81666f00-ffffffff81667166: fuse_add_dirent_to_cache (STB_LOCAL)
ffffffff820f258c-ffffffff820f25a7: fuse_add_dirent_to_cache.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fuse_add_dirent_to_cache(struct file *file, struct fuse_dirent *dirent, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/readdir.c (0)
Location: fs/fuse/readdir.c:32
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_emit
```
**Symbols:**

```
ffffffff816a1250-ffffffff816a14b3: fuse_add_dirent_to_cache (STB_LOCAL)
ffffffff821cf827-ffffffff821cf842: fuse_add_dirent_to_cache.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffff800010514754)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c06cf4c4)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (c00000000065cbd0)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffe00037e29c)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814282f2)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81418d72)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff81424492)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8143b5b2)
Location: fs/fuse/readdir.c:32
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_emit
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
