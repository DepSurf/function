# Function: <code>mpage_process_page_bufs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812968e0)
Location: fs/ext4/inode.c:2022
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
```
**Symbols:**

```
ffffffff812968e0-ffffffff812969e4: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c3f20)
Location: fs/ext4/inode.c:2179
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff812c3f20-ffffffff812c4024: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d95d0)
Location: fs/ext4/inode.c:2208
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff812d95d0-ffffffff812d96d4: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fd4f0)
Location: fs/ext4/inode.c:2285
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff812fd4f0-ffffffff812fd5ef: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81321d30)
Location: fs/ext4/inode.c:2293
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81321d30-ffffffff81321e2f: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8134fd60)
Location: fs/ext4/inode.c:2292
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff8134fd60-ffffffff8134fe5e: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81367f50)
Location: fs/ext4/inode.c:2322
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81367f50-ffffffff8136804f: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813914e0)
Location: fs/ext4/inode.c:2338
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff813914e0-ffffffff813915e8: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9e60)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff813a9e60-ffffffff813a9f74: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f5810)
Location: fs/ext4/inode.c:2166
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff813f5810-ffffffff813f58d5: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81407fc0)
Location: fs/ext4/inode.c:2186
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff81407fc0-ffffffff81408085: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e2b0)
Location: fs/ext4/inode.c:2185
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff8140e2b0-ffffffff8140e40c: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2164
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff81461440-ffffffff814615b2: mpage_process_page_bufs (STB_LOCAL)
ffffffff81cca76a-ffffffff81cca7d9: mpage_process_page_bufs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2196
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff814e01b0-ffffffff814e0329: mpage_process_page_bufs (STB_LOCAL)
ffffffff81e7d4aa-ffffffff81e7d519: mpage_process_page_bufs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2214
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_page
```
**Symbols:**

```
ffffffff81579470-ffffffff815795f6: mpage_process_page_bufs (STB_LOCAL)
ffffffff8206da17-ffffffff8206da86: mpage_process_page_bufs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1949
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_folio
```
**Symbols:**

```
ffffffff815b1250-ffffffff815b13ed: mpage_process_page_bufs (STB_LOCAL)
ffffffff820ed7c2-ffffffff820ed831: mpage_process_page_bufs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1953
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_process_folio
```
**Symbols:**

```
ffffffff815ea080-ffffffff815ea21a: mpage_process_page_bufs (STB_LOCAL)
ffffffff821ca8f7-ffffffff821ca966: mpage_process_page_bufs.cold (STB_LOCAL)
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
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047d870)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffff80001047d870-ffff80001047d9e4: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c06406c4)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
c06406c4-c0640898: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a1300)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
c0000000005a1300-c0000000005a14f4: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000307640)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffe000307640-ffffffe00030775e: mpage_process_page_bufs (STB_LOCAL)
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
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2440)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff813a2440-ffffffff813a2554: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392ed0)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff81392ed0-ffffffff81392fe4: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139fca0)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff8139fca0-ffffffff8139fdb4: mpage_process_page_bufs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpage_process_page_bufs(struct mpage_da_data *mpd, struct buffer_head *head, struct buffer_head *bh, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b4980)
Location: fs/ext4/inode.c:2316
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_prepare_extent_to_map
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
**Symbols:**

```
ffffffff813b4980-ffffffff813b4a94: mpage_process_page_bufs (STB_LOCAL)
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
