# Function: <code>fuse_conn_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131a9a0)
Location: fs/fuse/inode.c:637
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff8131a9a0-ffffffff8131a9b2: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8135053d)
Location: fs/fuse/inode.c:647
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff8134f470-ffffffff8134f482: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81365e9d)
Location: fs/fuse/inode.c:648
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff81364d90-ffffffff81364da2: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137a67d)
Location: fs/fuse/inode.c:641
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_alloc
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff813794b0-ffffffff813794c2: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139e350)
Location: fs/fuse/inode.c:641
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_alloc
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff8139e350-ffffffff8139e368: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813cd700)
Location: fs/fuse/inode.c:644
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_alloc
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff813cd700-ffffffff813cd718: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e6ad0)
Location: fs/fuse/inode.c:647
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_alloc
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff813e6ad0-ffffffff813e6ae8: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81412b00)
Location: fs/fuse/inode.c:645
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_alloc
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff81412b00-ffffffff81412b18: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142c780)
Location: fs/fuse/inode.c:647
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff8142c780-ffffffff8142c798: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147e0d5)
Location: fs/fuse/inode.c:662
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8147d240-ffffffff8147d298: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499421)
Location: fs/fuse/inode.c:738
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81498450-ffffffff814984a8: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149e661)
Location: fs/fuse/inode.c:778
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8149d680-ffffffff8149d6d8: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6991)
Location: fs/fuse/inode.c:831
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff814f51a0-ffffffff814f51f8: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff815867ce)
Location: fs/fuse/inode.c:873
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff815850f0-ffffffff81585163: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162ca46)
Location: fs/fuse/inode.c:886
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8162b2c0-ffffffff8162b333: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81664c7b)
Location: fs/fuse/inode.c:886
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff816634f0-ffffffff81663563: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169ef74)
Location: fs/fuse/inode.c:962
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_fill_super_common
  - fs/fuse/inode.c:fuse_get_tree_submount
Direct callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8169d5e0-ffffffff8169d653: fuse_conn_get (STB_GLOBAL)
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
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff80001051222c)
Location: fs/fuse/inode.c:647
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_install
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffff800010510db0-ffff800010510de0: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cc1a0)
Location: fs/fuse/inode.c:647
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_install
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
c06cc164-c06cc18c: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c000000000658224)
Location: fs/fuse/inode.c:647
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_install
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
c000000000658130-c000000000658150: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037c42e)
Location: fs/fuse/inode.c:647
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_dev_install
Direct callers:
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffe00037aeec-ffffffe00037af18: fuse_conn_get (STB_GLOBAL)
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
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81424d60)
Location: fs/fuse/inode.c:647
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff81424d60-ffffffff81424d78: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814157e0)
Location: fs/fuse/inode.c:647
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff814157e0-ffffffff814157f8: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81420f00)
Location: fs/fuse/inode.c:647
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff81420f00-ffffffff81420f18: fuse_conn_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fuse_conn *fuse_conn_get(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81437d20)
Location: fs/fuse/inode.c:647
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_dev_install
  - fs/fuse/control.c:fuse_ctl_file_conn_get
```
**Symbols:**

```
ffffffff81437d20-ffffffff81437d38: fuse_conn_get (STB_GLOBAL)
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
