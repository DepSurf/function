# Function: <code>kernfs_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81289080)
Location: fs/kernfs/inode.c:333
Inline: False
Direct callers:
  - kernel/cgroup.c:__cgroup_procs_write
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff81289080-ffffffff81289182: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812b6580)
Location: fs/kernfs/inode.c:337
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff812b6580-ffffffff812b667b: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cbdb0)
Location: fs/kernfs/inode.c:264
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff812cbdb0-ffffffff812cbeaa: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d9200)
Location: fs/kernfs/inode.c:264
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff812d9200-ffffffff812d9300: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fda60)
Location: fs/kernfs/inode.c:265
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff812fda60-ffffffff812fdb6b: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b6c0)
Location: fs/kernfs/inode.c:265
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff8132b6c0-ffffffff8132b7c7: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81342a20)
Location: fs/kernfs/inode.c:265
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_mount_ns
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff81342a20-ffffffff81342b27: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136ab90)
Location: fs/kernfs/inode.c:247
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff8136ab90-ffffffff8136aca0: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382d50)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff81382d50-ffffffff81382e60: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd7d0)
Location: fs/kernfs/inode.c:248
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff813cd7d0-ffffffff813cd818: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df400)
Location: fs/kernfs/inode.c:248
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff813df400-ffffffff813df448: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5fd0)
Location: fs/kernfs/inode.c:250
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff813e5fd0-ffffffff813e60e2: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81437bd0)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff81437bd0-ffffffff81437ce5: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b2930)
Location: fs/kernfs/inode.c:250
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff814b2930-ffffffff814b2a4e: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81549510)
Location: fs/kernfs/inode.c:248
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff81549510-ffffffff8154962e: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815810f0)
Location: fs/kernfs/inode.c:248
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff815810f0-ffffffff8158120b: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b9ba0)
Location: fs/kernfs/inode.c:247
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff815b9ba0-ffffffff815b9ca0: kernfs_get_inode (STB_GLOBAL)
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
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff800010451238)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffff800010451238-ffff80001045136c: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0614200)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
c0614200-c0614368: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569880)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
c000000000569880-c000000000569a20: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e40f4)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffe0002e40f4-ffffffe0002e420a: kernfs_get_inode (STB_GLOBAL)
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
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b330)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff8137b330-ffffffff8137b440: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136be00)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff8136be00-ffffffff8136bf10: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378e00)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff81378e00-ffffffff81378f10: kernfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *kernfs_get_inode(struct super_block *sb, struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138c8b0)
Location: fs/kernfs/inode.c:246
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - fs/kernfs/mount.c:kernfs_get_tree
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_get_inode
  - fs/kernfs/dir.c:kernfs_iop_lookup
```
**Symbols:**

```
ffffffff8138c8b0-ffffffff8138c9c0: kernfs_get_inode (STB_GLOBAL)
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
