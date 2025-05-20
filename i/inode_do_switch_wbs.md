# Function: <code>inode_do_switch_wbs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool inode_do_switch_wbs(struct inode *inode, struct bdi_writeback *old_wb, struct bdi_writeback *new_wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813ae070)
Location: fs/fs-writeback.c:369
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff813ae070-ffffffff813ae54e: inode_do_switch_wbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool inode_do_switch_wbs(struct inode *inode, struct bdi_writeback *old_wb, struct bdi_writeback *new_wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81432360)
Location: fs/fs-writeback.c:370
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81432360-ffffffff81432929: inode_do_switch_wbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inode_do_switch_wbs(struct inode *inode, struct bdi_writeback *old_wb, struct bdi_writeback *new_wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c03c0)
Location: fs/fs-writeback.c:372
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff814c03c0-ffffffff814c090f: inode_do_switch_wbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inode_do_switch_wbs(struct inode *inode, struct bdi_writeback *old_wb, struct bdi_writeback *new_wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f57b0)
Location: fs/fs-writeback.c:372
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff814f57b0-ffffffff814f5cdb: inode_do_switch_wbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inode_do_switch_wbs(struct inode *inode, struct bdi_writeback *old_wb, struct bdi_writeback *new_wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81529ec0)
Location: fs/fs-writeback.c:372
Inline: False
Direct callers:
  - fs/fs-writeback.c:inode_switch_wbs_work_fn
```
**Symbols:**

```
ffffffff81529ec0-ffffffff8152a3e3: inode_do_switch_wbs (STB_LOCAL)
```
</details>
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
