# Function: <code>dm_io_rewind</code>

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
void dm_io_rewind(struct dm_io *io, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io-rewind.c (0)
Location: drivers/md/dm-io-rewind.c:145
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_requeue_work
```
**Symbols:**

```
ffffffff820a87e8-ffffffff820a8919: dm_io_rewind.cold (STB_LOCAL)
ffffffff81d1fcf0-ffffffff81d1ffe3: dm_io_rewind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dm_io_rewind(struct dm_io *io, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io-rewind.c (0)
Location: drivers/md/dm-io-rewind.c:143
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_requeue_work
```
**Symbols:**

```
ffffffff821299fa-ffffffff82129b09: dm_io_rewind.cold (STB_LOCAL)
ffffffff81d88ee0-ffffffff81d891e7: dm_io_rewind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dm_io_rewind(struct dm_io *io, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-io-rewind.c (0)
Location: drivers/md/dm-io-rewind.c:143
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_requeue_work
```
**Symbols:**

```
ffffffff8220b74e-ffffffff8220b85d: dm_io_rewind.cold (STB_LOCAL)
ffffffff81e40620-ffffffff81e40927: dm_io_rewind (STB_GLOBAL)
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
