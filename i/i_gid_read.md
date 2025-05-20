# Function: <code>i_gid_read</code>

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
In fs/ext4/inode.c (ffffffff8129b0f5)
Location: include/linux/fs.h:1371
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_mark_iloc_dirty
```
```
In fs/ext4/super.c (ffffffff812b4ef5)
Location: include/linux/fs.h:1371
Inline: True
Inline callers:
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:perf_trace_ext4_free_inode
```
```
In fs/ext4/migrate.c (ffffffff812cc6d5)
Location: include/linux/fs.h:1371
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/inode.c (ffffffff812c7449)
Location: include/linux/fs.h:1448
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff812dd6b3)
Location: include/linux/fs.h:1448
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/migrate.c (ffffffff812fc01b)
Location: include/linux/fs.h:1448
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/inode.c (ffffffff812dcfa9)
Location: include/linux/fs.h:1413
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/super.c (ffffffff812f31f1)
Location: include/linux/fs.h:1413
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/migrate.c (ffffffff81311fcb)
Location: include/linux/fs.h:1413
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
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
In fs/ext4/inode.c (ffffffff812fed89)
Location: include/linux/fs.h:1430
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff81313a7b)
Location: include/linux/fs.h:1430
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81328442)
Location: include/linux/fs.h:1430
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8133b912)
Location: include/linux/fs.h:1430
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/inode.c (ffffffff81323539)
Location: include/linux/fs.h:1459
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff8133823b)
Location: include/linux/fs.h:1459
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8134c8b8)
Location: include/linux/fs.h:1459
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8135fd37)
Location: include/linux/fs.h:1459
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
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
In fs/ext4/inode.c (ffffffff81351aaa)
Location: include/linux/fs.h:1469
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813667c2)
Location: include/linux/fs.h:1469
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8137a860)
Location: include/linux/fs.h:1469
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8138df07)
Location: include/linux/fs.h:1469
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff81369566)
Location: include/linux/fs.h:1524
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff8137ec14)
Location: include/linux/fs.h:1524
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81392ec0)
Location: include/linux/fs.h:1524
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813a649f)
Location: include/linux/fs.h:1524
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff81392983)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813a805b)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813bcd47)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813d0d35)
Location: include/linux/fs.h:1540
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff813ab312)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813c0eb0)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813d6017)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813ea405)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff813f7676)
Location: include/linux/fs.h:1591
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8140d45b)
Location: include/linux/fs.h:1591
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81422737)
Location: include/linux/fs.h:1591
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff81436105)
Location: include/linux/fs.h:1591
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
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
In fs/ext4/inode.c (ffffffff8140a72a)
Location: include/linux/fs.h:1562
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff814208bb)
Location: include/linux/fs.h:1562
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81439947)
Location: include/linux/fs.h:1562
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8144eb45)
Location: include/linux/fs.h:1562
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
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
In fs/ext4/inode.c (ffffffff814108f3)
Location: include/linux/fs.h:1565
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8142706d)
Location: include/linux/fs.h:1565
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8143faf7)
Location: include/linux/fs.h:1565
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff814559a7)
Location: include/linux/fs.h:1565
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff8146362b)
Location: include/linux/fs.h:1615
Inline: True
```
```
In fs/ext4/migrate.c (ffffffff8147acfd)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81493787)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff814a99c7)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff815a0d0c)
Location: include/linux/fs.h:1615
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
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
In fs/ext4/inode.c (ffffffff814e238c)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff814fd12a)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81518986)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff81531d29)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81646c62)
Location: include/linux/fs.h:1583
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
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
In fs/ext4/inode.c (ffffffff8157b77c)
Location: include/linux/fs.h:1622
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff815978ed)
Location: include/linux/fs.h:1622
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815b4573)
Location: include/linux/fs.h:1622
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff815ce7b3)
Location: include/linux/fs.h:1622
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff816ff392)
Location: include/linux/fs.h:1622
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
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
In fs/ext4/inode.c (ffffffff815b2b7c)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff815ce325)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815eb2d3)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff81606083)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81739405)
Location: include/linux/fs.h:1302
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
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
In fs/ext4/inode.c (ffffffff815eb97c)
Location: include/linux/fs.h:1347
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/ext4/migrate.c (ffffffff81606ba5)
Location: include/linux/fs.h:1347
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81623cc3)
Location: include/linux/fs.h:1347
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff8163eda3)
Location: include/linux/fs.h:1347
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_create
```
```
In security/integrity/ima/ima_template_lib.c (ffffffff81779f25)
Location: include/linux/fs.h:1347
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:ima_eventinodegid_init
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
In fs/ext4/inode.c (ffff80001047fbb0)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffff8000104986e0)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffff8000104b7d68)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffff8000104c2994)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (c0640f34)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (c0659f04)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0670db0)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (c06875d8)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (c0000000005a39c4)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (c0000000005c2610)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0000000005deed4)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (c0000000005fa924)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffe0003089dc)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffe00031c46e)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffe00032cbd0)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffe00033e1b6)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff813a38f2)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813b9490)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813ce5f7)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813e29e5)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff81394382)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813a9f20)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813bf077)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813d3465)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff813a1152)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813b6cf0)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813cba87)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813dfd65)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
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
In fs/ext4/inode.c (ffffffff813b5d63)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/ext4/migrate.c (ffffffff813cba00)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813e0cd7)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_free_inode
  - fs/ext4/super.c:perf_trace_ext4_other_inode_update_time
  - fs/ext4/super.c:trace_event_raw_event_ext4_free_inode
  - fs/ext4/super.c:trace_event_raw_event_ext4_other_inode_update_time
```
```
In fs/ext4/xattr.c (ffffffff813f5185)
Location: include/linux/fs.h:1566
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
</details>
</li>
</ul>

## Differences
