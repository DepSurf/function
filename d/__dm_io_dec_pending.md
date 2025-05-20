# Function: <code>__dm_io_dec_pending</code>

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
In drivers/md/dm.c (ffffffff81b72281)
Location: drivers/md/dm.c:968
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0ebbe)
Location: drivers/md/dm.c:1046
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d77f8e)
Location: drivers/md/dm.c:1053
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2f1be)
Location: drivers/md/dm.c:1039
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_poll_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:__map_bio
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:clone_endio
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
