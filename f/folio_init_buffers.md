# Function: <code>folio_init_buffers</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
sector_t folio_init_buffers(struct folio *folio, struct block_device *bdev, sector_t block, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:1008
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
**Symbols:**

```
ffffffff815089e0-ffffffff81508abc: folio_init_buffers (STB_LOCAL)
ffffffff820e87c4-ffffffff820e87e0: folio_init_buffers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
sector_t folio_init_buffers(struct folio *folio, struct block_device *bdev, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/buffer.c (0)
Location: fs/buffer.c:996
Inline: False
Direct callers:
  - fs/buffer.c:__getblk_slow
  - fs/buffer.c:__getblk_slow
```
**Symbols:**

```
ffffffff8153d830-ffffffff8153d920: folio_init_buffers (STB_LOCAL)
ffffffff821c55a3-ffffffff821c55c7: folio_init_buffers.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>sector_t block</code>
</li>
<li>
<b>Param reordered. </b>
<code>folio, bdev, block, size</code> ➡️ <code>folio, bdev, size</code>
</li>
<li>
<b>Param type changed. </b>
<code>int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
</li>
</ul>
