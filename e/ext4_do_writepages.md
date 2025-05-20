# Function: <code>ext4_do_writepages</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_do_writepages(struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2721
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_normal_submit_inode_data_buffers
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81581d20-ffffffff8158252d: ext4_do_writepages (STB_LOCAL)
ffffffff8206e2ed-ffffffff8206e350: ext4_do_writepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_do_writepages(struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2508
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_normal_submit_inode_data_buffers
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff815b8910-ffffffff815b90b4: ext4_do_writepages (STB_LOCAL)
ffffffff820ee017-ffffffff820ee094: ext4_do_writepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_do_writepages(struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2511
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_normal_submit_inode_data_buffers
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff815f16a0-ffffffff815f1e35: ext4_do_writepages (STB_LOCAL)
ffffffff821cb172-ffffffff821cb1ef: ext4_do_writepages.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
