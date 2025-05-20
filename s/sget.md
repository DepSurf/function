# Function: <code>sget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120f990)
Location: fs/super.c:528
Inline: True
Inline callers:
  - fs/super.c:mount_ns
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_single
Direct callers:
  - fs/libfs.c:mount_pseudo
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8120f990-ffffffff8120f9ba: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81236440)
Location: fs/super.c:536
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/libfs.c:mount_pseudo
  - fs/devpts/inode.c:devpts_mount
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81236440-ffffffff812364cc: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812490e0)
Location: fs/super.c:535
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812490e0-ffffffff8124917a: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812549d0)
Location: fs/super.c:538
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812549d0-ffffffff81254a6a: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81276b60)
Location: fs/super.c:538
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81276b60-ffffffff81276bfa: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129d560)
Location: fs/super.c:548
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8129d560-ffffffff8129d604: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b24f0)
Location: fs/super.c:552
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812b24f0-ffffffff812b2594: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cee00)
Location: fs/super.c:570
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812cee00-ffffffff812cf008: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0830)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812e0830-ffffffff812e0a38: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317ac0)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81317ac0-ffffffff81317cc8: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81322d20)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81322d20-ffffffff81322fce: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81328de0)
Location: fs/super.c:577
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81328de0-ffffffff8132908e: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376410)
Location: fs/super.c:577
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff81376410-ffffffff813766be: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f5b80)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff813f5b80-ffffffff813f5e74: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147ee20)
Location: fs/super.c:619
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff8147ee20-ffffffff8147f114: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b3ae0)
Location: fs/super.c:626
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff814b3ae0-ffffffff814b3d7b: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6200)
Location: fs/super.c:803
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff814e6200-ffffffff814e6541: sget (STB_GLOBAL)
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
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010387470)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffff800010387470-ffff8000103876dc: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c05705f4)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
c05705f4-c0570840: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047e770)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
c00000000047e770-c00000000047eab8: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025a4ca)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffe00025a4ca-ffffffe00025a74a: sget (STB_GLOBAL)
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
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8e10)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812d8e10-ffffffff812d9018: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9a90)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812c9a90-ffffffff812c9c98: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6c20)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812d6c20-ffffffff812d6e28: sget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *sget(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7e90)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/ecryptfs/main.c:ecryptfs_mount
```
**Symbols:**

```
ffffffff812e7e90-ffffffff812e8091: sget (STB_GLOBAL)
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
