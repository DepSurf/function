# Function: <code>dm_cleanup_zoned_dev</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81a05c86)
Location: drivers/md/dm-zone.c:141
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
Direct callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81a05b70-ffffffff81a05be3: dm_cleanup_zoned_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81b6d996)
Location: drivers/md/dm-zone.c:140
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
Direct callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81b6d880-ffffffff81b6d8f9: dm_cleanup_zoned_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09dcb)
Location: drivers/md/dm-zone.c:140
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81d09c60-ffffffff81d09ceb: dm_cleanup_zoned_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d72f1a)
Location: drivers/md/dm-zone.c:141
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81d72db0-ffffffff81d72e3b: dm_cleanup_zoned_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dm_cleanup_zoned_dev(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81e2a01a)
Location: drivers/md/dm-zone.c:141
Inline: True
Inline callers:
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
  - drivers/md/dm-zone.c:dm_set_zones_restrictions
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
```
**Symbols:**

```
ffffffff81e29eb0-ffffffff81e29f3b: dm_cleanup_zoned_dev (STB_GLOBAL)
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
