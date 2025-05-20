# Function: <code>device_not_nowait_capable</code>

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
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81980040)
Location: drivers/md/dm-table.c:1691
Inline: False
```
**Symbols:**

```
ffffffff81980040-ffffffff81980071: device_not_nowait_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81964180)
Location: drivers/md/dm-table.c:1887
Inline: False
```
**Symbols:**

```
ffffffff81964180-ffffffff819641aa: device_not_nowait_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c130)
Location: drivers/md/dm-table.c:1882
Inline: False
```
**Symbols:**

```
ffffffff81a0c130-ffffffff81a0c15a: device_not_nowait_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b747f0)
Location: drivers/md/dm-table.c:1869
Inline: False
```
**Symbols:**

```
ffffffff81b747f0-ffffffff81b7481c: device_not_nowait_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11710)
Location: drivers/md/dm-table.c:1856
Inline: False
```
**Symbols:**

```
ffffffff81d11710-ffffffff81d1173c: device_not_nowait_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7ab70)
Location: drivers/md/dm-table.c:1843
Inline: False
```
**Symbols:**

```
ffffffff81d7ab70-ffffffff81d7ab9c: device_not_nowait_capable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_not_nowait_capable(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e31c80)
Location: drivers/md/dm-table.c:1880
Inline: False
```
**Symbols:**

```
ffffffff81e31c80-ffffffff81e31ca9: device_not_nowait_capable (STB_LOCAL)
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
