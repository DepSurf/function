# Function: <code>take_dentry_name_snapshot</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126af60)
Location: fs/dcache.c:285
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8126af60-ffffffff8126afde: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128d7e0)
Location: fs/dcache.c:285
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8128d7e0-ffffffff8128d85e: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5430)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff812b5430-ffffffff812b549f: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca8c0)
Location: fs/dcache.c:284
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812ca8c0-ffffffff812ca92f: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6990)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812e6990-ffffffff812e69fd: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f84f0)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812f84f0-ffffffff812f855d: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81331280)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff81331280-ffffffff813312ed: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133cc10)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff8133cc10-ffffffff8133cc7d: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343030)
Location: fs/dcache.c:288
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff81343030-ffffffff8134309d: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81390990)
Location: fs/dcache.c:288
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff81390990-ffffffff813909fd: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411460)
Location: fs/dcache.c:313
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff81411460-ffffffff814114f4: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149c610)
Location: fs/dcache.c:313
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff8149c610-ffffffff8149c6a4: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:313
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff820e81c7-ffffffff820e81e4: take_dentry_name_snapshot.cold (STB_LOCAL)
ffffffff814d1960-ffffffff814d1a2e: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:312
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/debugfs/inode.c:debugfs_rename
```
**Symbols:**

```
ffffffff821c4f04-ffffffff821c4f21: take_dentry_name_snapshot.cold (STB_LOCAL)
ffffffff81504330-ffffffff815043fe: take_dentry_name_snapshot (STB_GLOBAL)
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
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5ff0)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffff8000103a5ff0-ffff8000103a60dc: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0586e90)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
c0586e90-c0586f24: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0fb0)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
c0000000004a0fb0-c0000000004a10d0: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c8ec)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffe00026c8ec-ffffffe00026c99a: take_dentry_name_snapshot (STB_GLOBAL)
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
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0ad0)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812f0ad0-ffffffff812f0b3d: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1700)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812e1700-ffffffff812e176d: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee8e0)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812ee8e0-ffffffff812ee94d: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void take_dentry_name_snapshot(struct name_snapshot *name, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fee80)
Location: fs/dcache.c:286
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/notify/fsnotify.c:__fsnotify_parent
```
**Symbols:**

```
ffffffff812fee80-ffffffff812feef8: take_dentry_name_snapshot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
