# Function: <code>fuse_conn_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8131b460)
Location: fs/fuse/inode.c:625
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
```
**Symbols:**

```
ffffffff8131b460-ffffffff8131b4bd: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8134ff30)
Location: fs/fuse/inode.c:635
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8134ff30-ffffffff8134ff8e: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81365860)
Location: fs/fuse/inode.c:636
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81365860-ffffffff813658be: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81379f90)
Location: fs/fuse/inode.c:629
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81379f90-ffffffff81379fee: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8139ee30)
Location: fs/fuse/inode.c:629
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8139ee30-ffffffff8139ee8e: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813ce1a0)
Location: fs/fuse/inode.c:632
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813ce1a0-ffffffff813ce1fe: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e7af0)
Location: fs/fuse/inode.c:635
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff813e7af0-ffffffff813e7b4e: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81413ab0)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81413ab0-ffffffff81413b14: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142dad0)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8142dad0-ffffffff8142db3c: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147cd10)
Location: fs/fuse/inode.c:648
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8147cd10-ffffffff8147cdae: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81498110)
Location: fs/fuse/inode.c:722
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81498110-ffffffff814981c8: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149d340)
Location: fs/fuse/inode.c:762
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_dentry_automount
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8149d340-ffffffff8149d3f8: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f4d90)
Location: fs/fuse/inode.c:809
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff814f4d90-ffffffff814f4e69: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81584960)
Location: fs/fuse/inode.c:851
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81584960-ffffffff81584a56: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162aaa0)
Location: fs/fuse/inode.c:864
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8162aaa0-ffffffff8162ab96: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81662cc0)
Location: fs/fuse/inode.c:864
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81662cc0-ffffffff81662db6: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169cfe0)
Location: fs/fuse/inode.c:941
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_kill_sb_blk
  - fs/fuse/inode.c:fuse_kill_sb_anon
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff8169cfe0-ffffffff8169d091: fuse_conn_put (STB_GLOBAL)
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
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010512100)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffff800010512100-ffff800010512198: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06cd20c)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
c06cd20c-c06cd2a4: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c000000000659910)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
c000000000659910-c000000000659a20: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037c0a8)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffe00037c0a8-ffffffe00037c122: fuse_conn_put (STB_GLOBAL)
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
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814260b0)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff814260b0-ffffffff8142611c: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81416b30)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81416b30-ffffffff81416b9c: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81422250)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff81422250-ffffffff814222bc: fuse_conn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fuse_conn_put(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814390d0)
Location: fs/fuse/inode.c:633
Inline: True
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_dev_free
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_read
  - fs/fuse/control.c:fuse_conn_max_background_write
  - fs/fuse/control.c:fuse_conn_max_background_read
  - fs/fuse/control.c:fuse_conn_waiting_read
  - fs/fuse/control.c:fuse_conn_abort_write
```
**Symbols:**

```
ffffffff814390d0-ffffffff8143913c: fuse_conn_put (STB_GLOBAL)
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
