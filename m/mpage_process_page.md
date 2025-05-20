# Function: <code>mpage_process_page</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpage_process_page(struct mpage_da_data *mpd, struct page *page, ext4_lblk_t *m_lblk, ext4_fsblk_t *m_pblk, bool *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f5f00)
Location: fs/ext4/inode.c:2221
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff813f5f00-ffffffff813f605a: mpage_process_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpage_process_page(struct mpage_da_data *mpd, struct page *page, ext4_lblk_t *m_lblk, ext4_fsblk_t *m_pblk, bool *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81408860)
Location: fs/ext4/inode.c:2241
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81408860-ffffffff814089b9: mpage_process_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e8bd)
Location: fs/ext4/inode.c:2240
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mpage_process_page(struct mpage_da_data *mpd, struct page *page, ext4_lblk_t *m_lblk, ext4_fsblk_t *m_pblk, bool *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2219
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81461700-ffffffff8146185f: mpage_process_page (STB_LOCAL)
ffffffff81cca832-ffffffff81cca898: mpage_process_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mpage_process_page(struct mpage_da_data *mpd, struct page *page, ext4_lblk_t *m_lblk, ext4_fsblk_t *m_pblk, bool *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2251
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff814e0330-ffffffff814e048e: mpage_process_page (STB_LOCAL)
ffffffff81e7d519-ffffffff81e7d573: mpage_process_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mpage_process_page(struct mpage_da_data *mpd, struct page *page, ext4_lblk_t *m_lblk, ext4_fsblk_t *m_pblk, bool *map_bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2269
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81579610-ffffffff8157976e: mpage_process_page (STB_LOCAL)
ffffffff8206da86-ffffffff8206dae0: mpage_process_page.cold (STB_LOCAL)
```
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
