# Function: <code>mpage_map_one_extent</code>

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
Location: fs/ext4/inode.c:2150
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
Location: fs/ext4/inode.c:2307
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
Location: fs/ext4/inode.c:2336
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
Location: fs/ext4/inode.c:2416
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
Location: fs/ext4/inode.c:2419
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
In fs/ext4/inode.c (ffffffff81356167)
Location: fs/ext4/inode.c:2418
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
In fs/ext4/inode.c (ffffffff8136e433)
Location: fs/ext4/inode.c:2448
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813972aa)
Location: fs/ext4/inode.c:2464
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813afcda)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f96f0)
Location: fs/ext4/inode.c:2344
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff813f96f0-ffffffff813f985e: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140bcf0)
Location: fs/ext4/inode.c:2364
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff8140bcf0-ffffffff8140be46: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411eb0)
Location: fs/ext4/inode.c:2363
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff81411eb0-ffffffff81412006: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814679e6)
Location: fs/ext4/inode.c:2342
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e44d0)
Location: fs/ext4/inode.c:2372
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff814e44d0-ffffffff814e4650: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157d7b0)
Location: fs/ext4/inode.c:2389
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff8157d7b0-ffffffff8157d930: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b4aa0)
Location: fs/ext4/inode.c:2127
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff815b4aa0-ffffffff815b4c20: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mpage_map_one_extent(handle_t *handle, struct mpage_da_data *mpd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ed900)
Location: fs/ext4/inode.c:2131
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
**Symbols:**

```
ffffffff815ed900-ffffffff815eda80: mpage_map_one_extent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010484808)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0645e04)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
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
In fs/ext4/inode.c (c0000000005aa3d0)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030cb84)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a82ba)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398d4a)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5b1a)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ba27a)
Location: fs/ext4/inode.c:2445
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
