# Function: <code>dm_table_get_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a5121)
Location: drivers/md/dm-table.c:1539
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_any_congested
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff816a6eb0-ffffffff816a6ec2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81707421)
Location: drivers/md/dm-table.c:1641
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff817071f0-ffffffff81707202: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817392f1)
Location: drivers/md/dm-table.c:1642
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff817390c0-ffffffff817390d2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81752b81)
Location: drivers/md/dm-table.c:1869
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81752950-ffffffff81752962: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c4dc1)
Location: drivers/md/dm-table.c:1859
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff817c4b90-ffffffff817c4ba2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180d9ac)
Location: drivers/md/dm-table.c:1947
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff8180d750-ffffffff8180d762: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818398fc)
Location: drivers/md/dm-table.c:1940
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff818396a0-ffffffff818396b2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187c43c)
Location: drivers/md/dm-table.c:1986
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff8187c1e0-ffffffff8187c1f2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ae21c)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff818adfc0-ffffffff818adfd2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197e47c)
Location: drivers/md/dm-table.c:1962
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:retrieve_deps
```
**Symbols:**

```
ffffffff8197e220-ffffffff8197e232: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81980315)
Location: drivers/md/dm-table.c:1891
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:retrieve_deps
  - drivers/md/dm-ioctl.c:retrieve_deps
```
**Symbols:**

```
ffffffff81982860-ffffffff81982872: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff819644d5)
Location: drivers/md/dm-table.c:2088
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81966c80-ffffffff81966c92: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0c485)
Location: drivers/md/dm-table.c:2084
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81a0ee80-ffffffff81a0ee92: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b74ef5)
Location: drivers/md/dm-table.c:2075
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81b77570-ffffffff81b77588: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11fc5)
Location: drivers/md/dm-table.c:2046
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81d14960-ffffffff81d14978: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b395)
Location: drivers/md/dm-table.c:2032
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81d7da90-ffffffff81d7daa8: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e32315)
Location: drivers/md/dm-table.c:2069
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81e34e50-ffffffff81e34e68: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b04d00)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffff800010b04a70-ffff800010b04a98: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be3c90)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
c0be3a5c-c0be3a78: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf49c0)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
c000000000bf45f0-c000000000bf4600: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f3df6)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffe0006f3bfc-ffffffe0006f3c20: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8185409c)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81853e40-ffffffff81853e52: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181b6ac)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff8181b450-ffffffff8181b462: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a36cc)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff818a3470-ffffffff818a3482: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct list_head *dm_table_get_devices(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bf90c)
Location: drivers/md/dm-table.c:1984
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_any_congested
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff818bf6b0-ffffffff818bf6c2: dm_table_get_devices (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
