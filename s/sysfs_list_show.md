# Function: <code>sysfs_list_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sysfs_list_show(char *page, struct list_head *list, char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff813c7b00)
Location: block/blk-mq-sysfs.c:142
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_sysfs_rq_list_show
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_rq_list_show
```
**Symbols:**

```
ffffffff813c7b00-ffffffff813c7bc5: sysfs_list_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sysfs_list_show(char *page, struct list_head *list, char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff8140bf20)
Location: block/blk-mq-sysfs.c:142
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_rq_list_show
  - block/blk-mq-sysfs.c:blk_mq_sysfs_rq_list_show
```
**Symbols:**

```
ffffffff8140bf20-ffffffff8140bfe6: sysfs_list_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sysfs_list_show(char *page, struct list_head *list, char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81427320)
Location: block/blk-mq-sysfs.c:142
Inline: False
Direct callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_rq_list_show
  - block/blk-mq-sysfs.c:blk_mq_sysfs_rq_list_show
```
**Symbols:**

```
ffffffff81427320-ffffffff814273e6: sysfs_list_show (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
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
</ul>
