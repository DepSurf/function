# Function: <code>device_not_dax_capable</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819802b0)
Location: drivers/md/dm-table.c:823
Inline: False
```
**Symbols:**

```
ffffffff819802b0-ffffffff81980306: device_not_dax_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819643a0)
Location: drivers/md/dm-table.c:809
Inline: False
```
**Symbols:**

```
ffffffff819643a0-ffffffff819643f6: device_not_dax_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c380)
Location: drivers/md/dm-table.c:809
Inline: False
```
**Symbols:**

```
ffffffff81a0c380-ffffffff81a0c3a8: device_not_dax_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b753a0)
Location: drivers/md/dm-table.c:810
Inline: True
```
**Symbols:**

```
ffffffff81b753a0-ffffffff81b753f6: device_not_dax_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d124f0)
Location: drivers/md/dm-table.c:809
Inline: True
```
**Symbols:**

```
ffffffff81d124f0-ffffffff81d12546: device_not_dax_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b8b0)
Location: drivers/md/dm-table.c:804
Inline: True
```
**Symbols:**

```
ffffffff81d7b8b0-ffffffff81d7b906: device_not_dax_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int device_not_dax_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e32830)
Location: drivers/md/dm-table.c:825
Inline: True
```
**Symbols:**

```
ffffffff81e32830-ffffffff81e32886: device_not_dax_capable (STB_LOCAL)
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
