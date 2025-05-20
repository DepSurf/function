# Function: <code>i_uid_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129b0de)
Location: include/linux/fs.h:1366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/super.c (ffffffff812b4ede)
Location: include/linux/fs.h:1366
Inline: True
Inline callers:
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_free_inode
```
```
In fs/ext4/migrate.c (ffffffff812cc6a8)
Location: include/linux/fs.h:1366
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ecryptfs/main.c (ffffffff813038c0)
Location: include/linux/fs.h:1366
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c7432)
Location: include/linux/fs.h:1443
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff812dd69c)
Location: include/linux/fs.h:1443
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/migrate.c (ffffffff812fbfee)
Location: include/linux/fs.h:1443
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ecryptfs/main.c (ffffffff8133787a)
Location: include/linux/fs.h:1443
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dcf92)
Location: include/linux/fs.h:1408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff812f31da)
Location: include/linux/fs.h:1408
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/migrate.c (ffffffff81311f9e)
Location: include/linux/fs.h:1408
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ecryptfs/main.c (ffffffff8134d655)
Location: include/linux/fs.h:1408
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fed72)
Location: include/linux/fs.h:1425
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff81313a4e)
Location: include/linux/fs.h:1425
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81328429)
Location: include/linux/fs.h:1425
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8133b8f7)
Location: include/linux/fs.h:1425
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ecryptfs/main.c (ffffffff8136225e)
Location: include/linux/fs.h:1425
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81323522)
Location: include/linux/fs.h:1454
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff8133820e)
Location: include/linux/fs.h:1454
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8134c89f)
Location: include/linux/fs.h:1454
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8135fd1c)
Location: include/linux/fs.h:1454
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/ecryptfs/main.c (ffffffff81386e70)
Location: include/linux/fs.h:1454
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81351a96)
Location: include/linux/fs.h:1464
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813667b7)
Location: include/linux/fs.h:1464
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8137a847)
Location: include/linux/fs.h:1464
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8138def7)
Location: include/linux/fs.h:1464
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff813b5c15)
Location: include/linux/fs.h:1464
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81369553)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff8137ec08)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81392ea7)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813a648e)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff813cf172)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392971)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813a804e)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813bcd2f)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813d0d21)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff813f9cf0)
Location: include/linux/fs.h:1535
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ab300)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813c0ea3)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813d5fff)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813ea3f1)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff81413bc0)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f765b)
Location: include/linux/fs.h:1586
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8140d44e)
Location: include/linux/fs.h:1586
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8142271f)
Location: include/linux/fs.h:1586
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff814360ec)
Location: include/linux/fs.h:1586
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/ecryptfs/main.c (ffffffff81461d57)
Location: include/linux/fs.h:1586
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140a70f)
Location: include/linux/fs.h:1557
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff814208ae)
Location: include/linux/fs.h:1557
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8143992f)
Location: include/linux/fs.h:1557
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8144eb2c)
Location: include/linux/fs.h:1557
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/ecryptfs/main.c (ffffffff8147d8c7)
Location: include/linux/fs.h:1557
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814108d8)
Location: include/linux/fs.h:1560
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff81427060)
Location: include/linux/fs.h:1560
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8143fadf)
Location: include/linux/fs.h:1560
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8145598c)
Location: include/linux/fs.h:1560
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff81483481)
Location: include/linux/fs.h:1560
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81463612)
Location: include/linux/fs.h:1610
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8147acf0)
Location: include/linux/fs.h:1610
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8149376f)
Location: include/linux/fs.h:1610
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff814a99ac)
Location: include/linux/fs.h:1610
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff814dac01)
Location: include/linux/fs.h:1610
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff815a0c7c)
Location: include/linux/fs.h:1610
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e2373)
Location: include/linux/fs.h:1578
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff814fd11e)
Location: include/linux/fs.h:1578
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8151896d)
Location: include/linux/fs.h:1578
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff81531d0e)
Location: include/linux/fs.h:1578
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff81568571)
Location: include/linux/fs.h:1578
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81646bc2)
Location: include/linux/fs.h:1578
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157b763)
Location: include/linux/fs.h:1617
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff815978e1)
Location: include/linux/fs.h:1617
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815b455a)
Location: include/linux/fs.h:1617
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff815ce79d)
Location: include/linux/fs.h:1617
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/ecryptfs/main.c (ffffffff8160bcdf)
Location: include/linux/fs.h:1617
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff816ff2e2)
Location: include/linux/fs.h:1617
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b2b63)
Location: include/linux/fs.h:1297
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff815ce31a)
Location: include/linux/fs.h:1297
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815eb2ba)
Location: include/linux/fs.h:1297
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8160606d)
Location: include/linux/fs.h:1297
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/ecryptfs/main.c (ffffffff81643bbf)
Location: include/linux/fs.h:1297
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81739355)
Location: include/linux/fs.h:1297
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815eb963)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff81606b9a)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81623caa)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8163ed8d)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In fs/ecryptfs/main.c (ffffffff8167d14f)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81779e75)
Location: include/linux/fs.h:1342
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodeuid_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047fb94)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffff8000104986e0)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffff8000104b7d54)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffff8000104c2988)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffff8000104f5078)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0640f18)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (c0659f00)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0670d9c)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (c06875b8)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (c06b2920)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a39a4)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (c0000000005c25fc)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0000000005deebc)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (c0000000005fa904)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (c000000000635968)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe0003089cc)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffe00031c44e)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffe00032cbbc)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffe00033e1a6)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffe0003640e2)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a38e0)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813b9483)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813ce5df)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813e29d1)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff8140c1a0)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394370)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813a9f13)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813bf05f)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813d3451)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff813fcc20)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1140)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813b6ce3)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813cba6f)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813dfd51)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff81409520)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b5d51)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813cb9f3)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813e0cbf)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813f5171)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/ecryptfs/main.c (ffffffff8141f1e0)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ecryptfs/main.c:ecryptfs_mount
```
</details>
</li>
</ul>

## Differences
