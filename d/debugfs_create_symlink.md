# Function: <code>debugfs_create_symlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131d590)
Location: fs/debugfs/inode.c:492
Inline: False
```
**Symbols:**

```
ffffffff8131d590-ffffffff8131d643: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813520a0)
Location: fs/debugfs/inode.c:556
Inline: False
```
**Symbols:**

```
ffffffff813520a0-ffffffff81352156: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368350)
Location: fs/debugfs/inode.c:556
Inline: False
```
**Symbols:**

```
ffffffff81368350-ffffffff81368406: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137c940)
Location: fs/debugfs/inode.c:590
Inline: False
```
**Symbols:**

```
ffffffff8137c940-ffffffff8137c9f6: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1810)
Location: fs/debugfs/inode.c:593
Inline: False
```
**Symbols:**

```
ffffffff813a1810-ffffffff813a18c6: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d0ca0)
Location: fs/debugfs/inode.c:616
Inline: False
```
**Symbols:**

```
ffffffff813d0ca0-ffffffff813d0d62: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eb410)
Location: fs/debugfs/inode.c:619
Inline: False
```
**Symbols:**

```
ffffffff813eb410-ffffffff813eb4d1: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:638
Inline: False
```
**Symbols:**

```
ffffffff81417fdd-ffffffff81418004: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff81417360-ffffffff81417407: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffffffff81431e9d-ffffffff81431ec4: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff81431220-ffffffff814312c7: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:629
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff81481ad5-ffffffff81481afc: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff81481040-ffffffff814810e7: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:654
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff81bef848-ffffffff81bef86f: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff8149ec50-ffffffff8149ed21: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:658
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff81be18f1-ffffffff81be1918: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff814a4c30-ffffffff814a4d01: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:658
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff81cd24c7-ffffffff81cd2503: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff814fcd00-ffffffff814fcdf1: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:668
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff81e8560d-ffffffff81e85648: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff8158d530-ffffffff8158d62e: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:691
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff82072a41-ffffffff82072a55: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff81634390-ffffffff816344d0: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:691
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff820f26a5-ffffffff820f26b9: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff8166c6a0-ffffffff8166c7e0: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:709
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_debugfs.c:drm_debugfs_register
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
ffffffff821cf91d-ffffffff821cf932: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff816a6820-ffffffff816a697f: debugfs_create_symlink (STB_GLOBAL)
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
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010515ed8)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffff800010515ed8-ffff800010515fbc: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d0c90)
Location: fs/debugfs/inode.c:640
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_list_debug_create_link
```
**Symbols:**

```
c06d0c90-c06d0d5c: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065ea70)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
c00000000065ea70-c00000000065eb98: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037f68a)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffffffe00037f68a-ffffffe00037f75e: debugfs_create_symlink (STB_GLOBAL)
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
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffffffff8142a47d-ffffffff8142a4a4: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff81429800-ffffffff814298a7: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffffffff8141aefd-ffffffff8141af24: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff8141a280-ffffffff8141a327: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffffffff8142661d-ffffffff81426644: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff814259a0-ffffffff81425a47: debugfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_symlink(const char *name, struct dentry *parent, const char *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:640
Inline: False
```
**Symbols:**

```
ffffffff8143d4dd-ffffffff8143d504: debugfs_create_symlink.cold (STB_LOCAL)
ffffffff8143c860-ffffffff8143c907: debugfs_create_symlink (STB_GLOBAL)
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
