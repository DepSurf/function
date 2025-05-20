# Function: <code>device_is_rotational</code>

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
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197ff60)
Location: drivers/md/dm-table.c:1621
Inline: False
```
**Symbols:**

```
ffffffff8197ff60-ffffffff8197ff91: device_is_rotational (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819640c0)
Location: drivers/md/dm-table.c:1817
Inline: False
```
**Symbols:**

```
ffffffff819640c0-ffffffff819640ea: device_is_rotational (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c070)
Location: drivers/md/dm-table.c:1812
Inline: False
```
**Symbols:**

```
ffffffff81a0c070-ffffffff81a0c09a: device_is_rotational (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b74760)
Location: drivers/md/dm-table.c:1828
Inline: False
```
**Symbols:**

```
ffffffff81b74760-ffffffff81b7478c: device_is_rotational (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11690)
Location: drivers/md/dm-table.c:1818
Inline: False
```
**Symbols:**

```
ffffffff81d11690-ffffffff81d116bc: device_is_rotational (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7aaf0)
Location: drivers/md/dm-table.c:1805
Inline: False
```
**Symbols:**

```
ffffffff81d7aaf0-ffffffff81d7ab1c: device_is_rotational (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_is_rotational(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e31c00)
Location: drivers/md/dm-table.c:1842
Inline: False
```
**Symbols:**

```
ffffffff81e31c00-ffffffff81e31c29: device_is_rotational (STB_LOCAL)
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
