# Function: <code>dm_io_set_error</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b72c17)
Location: drivers/md/dm.c:974
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_io_set_error(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0c460)
Location: drivers/md/dm.c:1052
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d0c460-ffffffff81d0c4cb: dm_io_set_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_io_set_error(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d75650)
Location: drivers/md/dm.c:1059
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d75650-ffffffff81d756bb: dm_io_set_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_io_set_error(struct dm_io *io, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2c750)
Location: drivers/md/dm.c:1045
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81e2c750-ffffffff81e2c7bb: dm_io_set_error (STB_LOCAL)
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
