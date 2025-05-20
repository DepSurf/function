# Function: <code>debugfs_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131da80)
Location: fs/debugfs/inode.c:667
Inline: False
```
**Symbols:**

```
ffffffff8131da80-ffffffff8131dc91: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352520)
Location: fs/debugfs/inode.c:728
Inline: False
```
**Symbols:**

```
ffffffff81352520-ffffffff81352731: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813687d0)
Location: fs/debugfs/inode.c:728
Inline: False
```
**Symbols:**

```
ffffffff813687d0-ffffffff813689e4: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137cd60)
Location: fs/debugfs/inode.c:762
Inline: False
```
**Symbols:**

```
ffffffff8137cd60-ffffffff8137cfa0: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1c70)
Location: fs/debugfs/inode.c:786
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff813a1c70-ffffffff813a1eb0: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d0fa0)
Location: fs/debugfs/inode.c:809
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff813d0fa0-ffffffff813d11de: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eb630)
Location: fs/debugfs/inode.c:812
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff813eb630-ffffffff813eb8db: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81417710)
Location: fs/debugfs/inode.c:832
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff81417710-ffffffff814179dc: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814315d0)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff814315d0-ffffffff8143189c: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81481720)
Location: fs/debugfs/inode.c:727
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_migrate_dentry
```
**Symbols:**

```
ffffffff81481720-ffffffff814819e1: debugfs_rename.part.0 (STB_LOCAL)
ffffffff814819f0-ffffffff81481a2f: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149e7d0)
Location: fs/debugfs/inode.c:752
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_migrate_dentry
```
**Symbols:**

```
ffffffff8149e7d0-ffffffff8149ea4e: debugfs_rename.part.0 (STB_LOCAL)
ffffffff8149ea50-ffffffff8149ea8f: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a4790)
Location: fs/debugfs/inode.c:756
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff814a4790-ffffffff814a4a2b: debugfs_rename.part.0 (STB_LOCAL)
ffffffff814a4a30-ffffffff814a4a6f: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fc900)
Location: fs/debugfs/inode.c:756
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff814fc900-ffffffff814fcbc8: debugfs_rename.part.0 (STB_LOCAL)
ffffffff814fcbd0-ffffffff814fcc0f: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8158d070)
Location: fs/debugfs/inode.c:766
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff8158d070-ffffffff8158d411: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81633b70)
Location: fs/debugfs/inode.c:811
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff81633b70-ffffffff81633f11: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8166be70)
Location: fs/debugfs/inode.c:811
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff8166be70-ffffffff8166c22f: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816a6310)
Location: fs/debugfs/inode.c:858
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff816a6310-ffffffff816a66cf: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff8000105162f8)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffff8000105162f8-ffff8000105165b0: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d125c)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
c06d125c-c06d1530: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065f190)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
c00000000065f190-c00000000065f580: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037fa42)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffe00037fa42-ffffffe00037fc90: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81429bb0)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff81429bb0-ffffffff81429e7c: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8141a630)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff8141a630-ffffffff8141a8fc: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81425d50)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff81425d50-ffffffff8142601c: debugfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *debugfs_rename(struct dentry *old_dir, struct dentry *old_dentry, struct dentry *new_dir, const char *new_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8143cda0)
Location: fs/debugfs/inode.c:834
Inline: True
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_unregister
```
**Symbols:**

```
ffffffff8143cda0-ffffffff8143d06c: debugfs_rename (STB_GLOBAL)
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
