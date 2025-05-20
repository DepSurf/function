# Function: <code>mpage_map_and_submit_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129bcb9)
Location: fs/ext4/inode.c:2224
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c97b4)
Location: fs/ext4/inode.c:2382
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812df45d)
Location: fs/ext4/inode.c:2408
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8130364f)
Location: fs/ext4/inode.c:2488
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81328045)
Location: fs/ext4/inode.c:2491
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8135613a)
Location: fs/ext4/inode.c:2490
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136e405)
Location: fs/ext4/inode.c:2520
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81397260)
Location: fs/ext4/inode.c:2532
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81397260-ffffffff813976fd: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813afc90)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff813afc90-ffffffff813b0131: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fbc50)
Location: fs/ext4/inode.c:2412
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff813fbc50-ffffffff813fbe50: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140e370)
Location: fs/ext4/inode.c:2432
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff8140e370-ffffffff8140e57b: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81414600)
Location: fs/ext4/inode.c:2431
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81414600-ffffffff814148ef: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81467980-ffffffff81467e6b: mpage_map_and_submit_extent (STB_LOCAL)
ffffffff81ccaedd-ffffffff81ccaf60: mpage_map_and_submit_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2440
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff814e7640-ffffffff814e797d: mpage_map_and_submit_extent (STB_LOCAL)
ffffffff81e7dd73-ffffffff81e7ddee: mpage_map_and_submit_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2457
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff815819d0-ffffffff81581d0d: mpage_map_and_submit_extent (STB_LOCAL)
ffffffff8206e272-ffffffff8206e2ed: mpage_map_and_submit_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2195
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff815b85c0-ffffffff815b88fd: mpage_map_and_submit_extent (STB_LOCAL)
ffffffff820edf9c-ffffffff820ee017: mpage_map_and_submit_extent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:2199
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff815f1360-ffffffff815f168a: mpage_map_and_submit_extent (STB_LOCAL)
ffffffff821cb0f7-ffffffff821cb172: mpage_map_and_submit_extent.cold (STB_LOCAL)
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
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff8000104847a8)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffff8000104847a8-ffff800010484c28: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0645d5c)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
c0645d5c-c0646580: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005aa3b0)
Location: fs/ext4/inode.c:2513
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030cb44)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffe00030cb44-ffffffe00030cf90: mpage_map_and_submit_extent (STB_LOCAL)
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
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a8270)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff813a8270-ffffffff813a8711: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398d00)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81398d00-ffffffff813991a1: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5ad0)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff813a5ad0-ffffffff813a5f71: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mpage_map_and_submit_extent(handle_t *handle, struct mpage_da_data *mpd, bool *give_up_on_write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ba230)
Location: fs/ext4/inode.c:2513
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff813ba230-ffffffff813ba6ea: mpage_map_and_submit_extent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
