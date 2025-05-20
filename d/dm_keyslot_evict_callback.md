# Function: <code>dm_keyslot_evict_callback</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_keyslot_evict_callback(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819645f0)
Location: drivers/md/dm-table.c:1204
Inline: False
```
**Symbols:**

```
ffffffff819645f0-ffffffff81964625: dm_keyslot_evict_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_keyslot_evict_callback(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c5a0)
Location: drivers/md/dm-table.c:1199
Inline: False
```
**Symbols:**

```
ffffffff81a0c5a0-ffffffff81a0c5d5: dm_keyslot_evict_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_keyslot_evict_callback(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b75020)
Location: drivers/md/dm-table.c:1195
Inline: False
```
**Symbols:**

```
ffffffff81b75020-ffffffff81b7505e: dm_keyslot_evict_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_keyslot_evict_callback(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d12110)
Location: drivers/md/dm-table.c:1212
Inline: False
```
**Symbols:**

```
ffffffff81d12110-ffffffff81d12147: dm_keyslot_evict_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_keyslot_evict_callback(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b4d0)
Location: drivers/md/dm-table.c:1200
Inline: False
```
**Symbols:**

```
ffffffff81d7b4d0-ffffffff81d7b4f6: dm_keyslot_evict_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_keyslot_evict_callback(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e32450)
Location: drivers/md/dm-table.c:1222
Inline: False
```
**Symbols:**

```
ffffffff81e32450-ffffffff81e32476: dm_keyslot_evict_callback (STB_LOCAL)
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
