# Function: <code>ecryptfs_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81303180)
Location: fs/ecryptfs/main.c:491
Inline: False
```
**Symbols:**

```
ffffffff81303180-ffffffff8130399a: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81337100)
Location: fs/ecryptfs/main.c:490
Inline: False
```
**Symbols:**

```
ffffffff81337100-ffffffff81337955: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8134ced0)
Location: fs/ecryptfs/main.c:490
Inline: False
```
**Symbols:**

```
ffffffff8134ced0-ffffffff8134d730: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81361a30)
Location: fs/ecryptfs/main.c:490
Inline: False
```
**Symbols:**

```
ffffffff81361a30-ffffffff813622ce: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81386700)
Location: fs/ecryptfs/main.c:490
Inline: False
```
**Symbols:**

```
ffffffff81386700-ffffffff81386f4d: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:490
Inline: False
```
**Symbols:**

```
ffffffff813b5520-ffffffff813b5c39: ecryptfs_mount (STB_LOCAL)
ffffffff813b5d9d-ffffffff813b5eb4: ecryptfs_mount.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:490
Inline: False
```
**Symbols:**

```
ffffffff813cea40-ffffffff813cf1b1: ecryptfs_mount (STB_LOCAL)
ffffffff813cf31d-ffffffff813cf419: ecryptfs_mount.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff813f9a10-ffffffff813f9d73: ecryptfs_mount (STB_LOCAL)
ffffffff813f9fb8-ffffffff813f9fe4: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff814138e0-ffffffff81413c43: ecryptfs_mount (STB_LOCAL)
ffffffff81413e88-ffffffff81413eb4: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff81461a80-ffffffff81461de1: ecryptfs_mount (STB_LOCAL)
ffffffff81462042-ffffffff8146206e: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff8147d5f0-ffffffff8147d951: ecryptfs_mount (STB_LOCAL)
ffffffff81bee2b8-ffffffff81bee2e4: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff81483170-ffffffff8148351c: ecryptfs_mount (STB_LOCAL)
ffffffff81be03a1-ffffffff81be03e3: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff814da8f0-ffffffff814dac9c: ecryptfs_mount (STB_LOCAL)
ffffffff81cd0af6-ffffffff81cd0b38: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff81568240-ffffffff81568616: ecryptfs_mount (STB_LOCAL)
ffffffff81e83d48-ffffffff81e83d7c: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8160bac0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff8160bac0-ffffffff8160beed: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff816439a0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff816439a0-ffffffff81643dca: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8167cf30)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff8167cf30-ffffffff8167d35d: ecryptfs_mount (STB_LOCAL)
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
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffff8000104f4dd0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffff8000104f4dd0-ffff8000104f5130: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (c06b2660)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
c06b2660-c06b2a08: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (c000000000635650)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
c000000000635650-c000000000635a54: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffe000363eb0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffe000363eb0-ffffffe0003641a6: ecryptfs_mount (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff8140bec0-ffffffff8140c223: ecryptfs_mount (STB_LOCAL)
ffffffff8140c468-ffffffff8140c494: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff813fc940-ffffffff813fcca3: ecryptfs_mount (STB_LOCAL)
ffffffff813fcee8-ffffffff813fcf14: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff81409240-ffffffff814095a3: ecryptfs_mount (STB_LOCAL)
ffffffff814097e8-ffffffff81409814: ecryptfs_mount.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *ecryptfs_mount(struct file_system_type *fs_type, int flags, const char *dev_name, void *raw_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:476
Inline: False
```
**Symbols:**

```
ffffffff8141ef00-ffffffff8141f263: ecryptfs_mount (STB_LOCAL)
ffffffff8141f4a8-ffffffff8141f4d4: ecryptfs_mount.cold (STB_LOCAL)
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
