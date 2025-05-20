# Function: <code>ext4_da_release_space</code>

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
In fs/ext4/inode.c (ffffffff812973c0)
Location: fs/ext4/inode.c:1348
Inline: True
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
In fs/ext4/inode.c (ffffffff812c49f1)
Location: fs/ext4/inode.c:1505
Inline: True
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
In fs/ext4/inode.c (ffffffff812da0a1)
Location: fs/ext4/inode.c:1532
Inline: True
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
In fs/ext4/inode.c (ffffffff812fdf85)
Location: fs/ext4/inode.c:1585
Inline: True
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
In fs/ext4/inode.c (ffffffff81322775)
Location: fs/ext4/inode.c:1595
Inline: True
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
In fs/ext4/inode.c (ffffffff8135115b)
Location: fs/ext4/inode.c:1598
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136c110)
Location: fs/ext4/inode.c:1598
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_blks
```
**Symbols:**

```
ffffffff8136c110-ffffffff8136c233: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813956e0)
Location: fs/ext4/inode.c:1614
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_blks
```
**Symbols:**

```
ffffffff813956e0-ffffffff8139580f: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ae0b0)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff813ae0b0-ffffffff813ae1d3: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa080)
Location: fs/ext4/inode.c:1482
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff813fa080-ffffffff813fa1a3: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c680)
Location: fs/ext4/inode.c:1499
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff8140c680-ffffffff8140c78e: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412800)
Location: fs/ext4/inode.c:1498
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff81412800-ffffffff8141290e: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1486
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff81ccad66-ffffffff81ccada5: ext4_da_release_space.cold (STB_LOCAL)
ffffffff81465610-ffffffff8146573f: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1499
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff81e7dc0a-ffffffff81e7dc49: ext4_da_release_space.cold (STB_LOCAL)
ffffffff814e4f50-ffffffff814e50be: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1513
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff8206e0d3-ffffffff8206e112: ext4_da_release_space.cold (STB_LOCAL)
ffffffff8157e5c0-ffffffff8157e72e: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1471
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff820ede36-ffffffff820ede75: ext4_da_release_space.cold (STB_LOCAL)
ffffffff815b5fd0-ffffffff815b613e: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:1483
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff821caf91-ffffffff821cafd0: ext4_da_release_space.cold (STB_LOCAL)
ffffffff815eed70-ffffffff815eeede: ext4_da_release_space (STB_GLOBAL)
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
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010482aa8)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffff800010482aa8-ffff800010482c44: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0643f34)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
c0643f34-c06440d4: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a7750)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
c0000000005a7750-c0000000005a7908: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b2d8)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffe00030b2d8-ffffffe00030b43c: ext4_da_release_space (STB_GLOBAL)
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
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a6690)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff813a6690-ffffffff813a67b3: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81397120)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff81397120-ffffffff81397243: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3ef0)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff813a3ef0-ffffffff813a4013: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_da_release_space(struct inode *inode, int to_free);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b85c0)
Location: fs/ext4/inode.c:1633
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_remove_extent
```
**Symbols:**

```
ffffffff813b85c0-ffffffff813b86fa: ext4_da_release_space (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
