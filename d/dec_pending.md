# Function: <code>dec_pending</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a09f0)
Location: drivers/md/dm.c:930
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff816a09f0-ffffffff816a0c65: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81701d40)
Location: drivers/md/dm.c:764
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81701d40-ffffffff81701fd2: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81733b90)
Location: drivers/md/dm.c:764
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81733b90-ffffffff81733e14: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ccd0)
Location: drivers/md/dm.c:765
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8174ccd0-ffffffff8174cf18: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817beea0)
Location: drivers/md/dm.c:773
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff817beea0-ffffffff817bf0f5: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807560)
Location: drivers/md/dm.c:857
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81807560-ffffffff818077af: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833560)
Location: drivers/md/dm.c:912
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81833560-ffffffff8183375d: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81875490)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81875490-ffffffff81875696: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a7240)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818a7240-ffffffff818a7446: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81977d20)
Location: drivers/md/dm.c:907
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81977d20-ffffffff81977ed4: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197c9b0)
Location: drivers/md/dm.c:903
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8197c9b0-ffffffff8197cb64: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960840)
Location: drivers/md/dm.c:906
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81960840-ffffffff81960a88: dec_pending (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afe518)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffff800010afe518-ffff800010afe7ec: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdcc50)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c0bdcc50-c0bdce40: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beabf0)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c000000000beabf0-c000000000beaea8: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ed7aa)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffe0006ed7aa-ffffffe0006ed960: dec_pending (STB_LOCAL)
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
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184d0c0)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8184d0c0-ffffffff8184d2c6: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818146e0)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818146e0-ffffffff818148e6: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189c6f0)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8189c6f0-ffffffff8189c8f6: dec_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dec_pending(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b8930)
Location: drivers/md/dm.c:894
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818b8930-ffffffff818b8b36: dec_pending (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
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
