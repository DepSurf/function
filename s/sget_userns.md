# Function: <code>sget_userns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120f540)
Location: fs/super.c:459
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:mount_nodev
  - fs/super.c:mount_bdev
  - fs/super.c:mount_single
  - fs/proc/root.c:proc_mount
```
**Symbols:**

```
ffffffff8120f540-ffffffff8120f982: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235f70)
Location: fs/super.c:463
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/kernfs/mount.c:kernfs_mount_ns
```
**Symbols:**

```
ffffffff81235f70-ffffffff81236436: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248c40)
Location: fs/super.c:462
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
```
**Symbols:**

```
ffffffff81248c40-ffffffff812490da: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254550)
Location: fs/super.c:465
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
```
**Symbols:**

```
ffffffff81254550-ffffffff812549cd: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812766d0)
Location: fs/super.c:469
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
```
**Symbols:**

```
ffffffff812766d0-ffffffff81276b5f: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129d0b0)
Location: fs/super.c:483
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
```
**Symbols:**

```
ffffffff8129d0b0-ffffffff8129d553: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *sget_userns(struct file_system_type *type, int (*test)(struct super_block *, void *), int (*set)(struct super_block *, void *), int flags, struct user_namespace *user_ns, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b2060)
Location: fs/super.c:487
Inline: False
Direct callers:
  - fs/super.c:mount_ns
  - fs/super.c:sget
  - fs/libfs.c:mount_pseudo_xattr
  - fs/kernfs/mount.c:kernfs_mount_ns
```
**Symbols:**

```
ffffffff812b2060-ffffffff812b24ef: sget_userns (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
