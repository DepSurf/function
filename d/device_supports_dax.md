# Function: <code>device_supports_dax</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81704dd0)
Location: drivers/md/dm-table.c:848
Inline: False
```
**Symbols:**

```
ffffffff81704dd0-ffffffff81704e09: device_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81736c80)
Location: drivers/md/dm-table.c:842
Inline: False
```
**Symbols:**

```
ffffffff81736c80-ffffffff81736cb9: device_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81750000)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffff81750000-ffffffff81750031: device_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c21e0)
Location: drivers/md/dm-table.c:884
Inline: False
```
**Symbols:**

```
ffffffff817c21e0-ffffffff817c2211: device_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180af70)
Location: drivers/md/dm-table.c:885
Inline: False
```
**Symbols:**

```
ffffffff8180af70-ffffffff8180af8e: device_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81836f70)
Location: drivers/md/dm-table.c:883
Inline: False
```
**Symbols:**

```
ffffffff81836f70-ffffffff81836f8e: device_supports_dax (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81879b60)
Location: drivers/md/dm-table.c:884
Inline: False
```
**Symbols:**

```
ffffffff81879b60-ffffffff81879b85: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ab950)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffff818ab950-ffffffff818ab975: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197bc50)
Location: drivers/md/dm-table.c:865
Inline: False
```
**Symbols:**

```
ffffffff8197bc50-ffffffff8197bca3: device_supports_dax (STB_GLOBAL)
```
</details>
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
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b02230)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffff800010b02230-ffff800010b02280: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be0e08)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
c0be0e08-c0be0e24: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf10f0)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
c000000000bf10f0-c000000000bf1144: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f1b4e)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffe0006f1b4e-ffffffe0006f1b96: device_supports_dax (STB_GLOBAL)
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
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818517d0)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffff818517d0-ffffffff818517f5: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81818de0)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffff81818de0-ffffffff81818e05: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a0e00)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffff818a0e00-ffffffff818a0e25: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_supports_dax(struct dm_target *ti, struct dm_dev *dev, sector_t start, sector_t len, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bd040)
Location: drivers/md/dm-table.c:882
Inline: False
```
**Symbols:**

```
ffffffff818bd040-ffffffff818bd065: device_supports_dax (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
