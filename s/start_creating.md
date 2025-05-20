# Function: <code>start_creating</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131d400)
Location: fs/debugfs/inode.c:245
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8131eef0)
Location: fs/tracefs/inode.c:317
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8131d400-ffffffff8131d4f9: start_creating (STB_LOCAL)
ffffffff8131eef0-ffffffff8131efda: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81351f80)
Location: fs/debugfs/inode.c:251
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81354410)
Location: fs/tracefs/inode.c:317
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff81351f80-ffffffff81352093: start_creating (STB_LOCAL)
ffffffff81354410-ffffffff81354502: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368230)
Location: fs/debugfs/inode.c:251
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8136a6d0)
Location: fs/tracefs/inode.c:317
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff81368230-ffffffff81368343: start_creating (STB_LOCAL)
ffffffff8136a6d0-ffffffff8136a7c2: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137c830)
Location: fs/debugfs/inode.c:285
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8137ee70)
Location: fs/tracefs/inode.c:315
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8137c830-ffffffff8137c938: start_creating (STB_LOCAL)
ffffffff8137ee70-ffffffff8137ef62: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a1700)
Location: fs/debugfs/inode.c:287
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813a3eb0)
Location: fs/tracefs/inode.c:315
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff813a1700-ffffffff813a1808: start_creating (STB_LOCAL)
ffffffff813a3eb0-ffffffff813a3fa2: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d0ba0)
Location: fs/debugfs/inode.c:309
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813d3290)
Location: fs/tracefs/inode.c:315
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff813d0ba0-ffffffff813d0ca0: start_creating (STB_LOCAL)
ffffffff813d3290-ffffffff813d3384: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813eb310)
Location: fs/debugfs/inode.c:309
Inline: True
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff813eda60)
Location: fs/tracefs/inode.c:315
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff813eb310-ffffffff813eb410: start_creating (STB_LOCAL)
ffffffff813eda60-ffffffff813edb54: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:311
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81419c90)
Location: fs/tracefs/inode.c:311
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff81417200-ffffffff814172fb: start_creating (STB_LOCAL)
ffffffff81417f3b-ffffffff81417f95: start_creating.cold (STB_LOCAL)
ffffffff81419c90-ffffffff81419d83: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81433ae0)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff814310c0-ffffffff814311bb: start_creating (STB_LOCAL)
ffffffff81431dfb-ffffffff81431e55: start_creating.cold (STB_LOCAL)
ffffffff81433ae0-ffffffff81433bd3: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:309
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81483660)
Location: fs/tracefs/inode.c:312
Inline: False
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff81480ec0-ffffffff81480fd2: start_creating (STB_LOCAL)
ffffffff81481a2f-ffffffff81481a8d: start_creating.cold (STB_LOCAL)
ffffffff81483660-ffffffff8148376a: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8149ec7e)
Location: fs/debugfs/inode.c:313
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a0cd0)
Location: fs/tracefs/inode.c:312
Inline: False
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8149e650-ffffffff8149e762: start_creating.part.0 (STB_LOCAL)
ffffffff81bef7ea-ffffffff81bef848: start_creating.part.0.cold (STB_LOCAL)
ffffffff814a0cd0-ffffffff814a0dda: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814a4c5e)
Location: fs/debugfs/inode.c:317
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814a6e00)
Location: fs/tracefs/inode.c:314
Inline: False
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff814a4620-ffffffff814a472d: start_creating.part.0 (STB_LOCAL)
ffffffff81be1893-ffffffff81be18f1: start_creating.part.0.cold (STB_LOCAL)
ffffffff814a6e00-ffffffff814a6f09: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff814fcd30)
Location: fs/debugfs/inode.c:317
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff814fef60)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff814fc6a0-ffffffff814fc7ad: start_creating.part.0 (STB_LOCAL)
ffffffff81cd2455-ffffffff81cd24b3: start_creating.part.0.cold (STB_LOCAL)
ffffffff814fef60-ffffffff814ff069: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8158d55f)
Location: fs/debugfs/inode.c:317
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8158ff60)
Location: fs/tracefs/inode.c:387
Inline: False
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8158cdc0-ffffffff8158cef2: start_creating.part.0 (STB_LOCAL)
ffffffff81e8559b-ffffffff81e855f8: start_creating.part.0.cold (STB_LOCAL)
ffffffff8158ff60-ffffffff8159008d: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816343bf)
Location: fs/debugfs/inode.c:340
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81637300)
Location: fs/tracefs/inode.c:402
Inline: False
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff81633750-ffffffff816338ef: start_creating.part.0 (STB_LOCAL)
ffffffff81637300-ffffffff8163742d: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8166c6cf)
Location: fs/debugfs/inode.c:340
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8166f760)
Location: fs/tracefs/inode.c:402
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8166ba50-ffffffff8166bbef: start_creating.part.0 (STB_LOCAL)
ffffffff8166f760-ffffffff8166f88d: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (ffffffff816a684f)
Location: fs/debugfs/inode.c:347
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
**Symbols:**

```
ffffffff816a5e00-ffffffff816a5f9f: start_creating.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010515d28)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffff800010519560)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffff800010515d28-ffff800010515e80: start_creating (STB_LOCAL)
ffff800010519560-ffff800010519670: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d0ab0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c06d3c44)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
c06d0ab0-c06d0bfc: start_creating (STB_LOCAL)
c06d3c44-c06d3d24: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065e7e0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (c0000000006629b0)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
c00000000065e7e0-c00000000065e9e8: start_creating (STB_LOCAL)
c0000000006629b0-c000000000662b0c: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037f4dc)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffe0003828ca)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffe00037f4dc-ffffffe00037f636: start_creating (STB_LOCAL)
ffffffe0003828ca-ffffffe0003829c4: start_creating (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8142c0c0)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff814296a0-ffffffff8142979b: start_creating (STB_LOCAL)
ffffffff8142a3db-ffffffff8142a435: start_creating.cold (STB_LOCAL)
ffffffff8142c0c0-ffffffff8142c1b3: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8141cb40)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8141a120-ffffffff8141a21b: start_creating (STB_LOCAL)
ffffffff8141ae5b-ffffffff8141aeb5: start_creating.cold (STB_LOCAL)
ffffffff8141cb40-ffffffff8141cc33: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff81428260)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff81425840-ffffffff8142593b: start_creating (STB_LOCAL)
ffffffff8142657b-ffffffff814265d5: start_creating.cold (STB_LOCAL)
ffffffff81428260-ffffffff81428353: start_creating (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
struct dentry *start_creating(const char *name, struct dentry *parent);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:313
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
```
```
In fs/tracefs/inode.c (ffffffff8143f120)
Location: fs/tracefs/inode.c:312
Inline: True
Direct callers:
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
```
**Symbols:**

```
ffffffff8143c700-ffffffff8143c7fb: start_creating (STB_LOCAL)
ffffffff8143d43b-ffffffff8143d495: start_creating.cold (STB_LOCAL)
ffffffff8143f120-ffffffff8143f213: start_creating (STB_LOCAL)
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
