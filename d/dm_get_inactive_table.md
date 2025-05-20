# Function: <code>dm_get_inactive_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816a8890)
Location: drivers/md/dm-ioctl.c:645
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff816a8890-ffffffff816a88e7: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81708d20)
Location: drivers/md/dm-ioctl.c:645
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81708d20-ffffffff81708d77: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173abf0)
Location: drivers/md/dm-ioctl.c:645
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8173abf0-ffffffff8173ac47: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81754280)
Location: drivers/md/dm-ioctl.c:650
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81754280-ffffffff817542d7: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c6430)
Location: drivers/md/dm-ioctl.c:657
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff817c6430-ffffffff817c6487: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:657
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8180f0a0-ffffffff8180f0ef: dm_get_inactive_table (STB_LOCAL)
ffffffff81811753-ffffffff81811766: dm_get_inactive_table.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:657
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8183b080-ffffffff8183b0cf: dm_get_inactive_table (STB_LOCAL)
ffffffff8183d753-ffffffff8183d766: dm_get_inactive_table.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:657
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8187dd80-ffffffff8187ddd3: dm_get_inactive_table (STB_LOCAL)
ffffffff8188033a-ffffffff8188034e: dm_get_inactive_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff818afda0-ffffffff818afdf3: dm_get_inactive_table (STB_LOCAL)
ffffffff818b21fa-ffffffff818b220e: dm_get_inactive_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81981f56)
Location: drivers/md/dm-ioctl.c:682
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81986576)
Location: drivers/md/dm-ioctl.c:682
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8196ab76)
Location: drivers/md/dm-ioctl.c:759
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81a13036)
Location: drivers/md/dm-ioctl.c:764
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81b7b8a6)
Location: drivers/md/dm-ioctl.c:765
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
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
In drivers/md/dm-ioctl.c (ffffffff81d18d3a)
Location: drivers/md/dm-ioctl.c:765
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:__dev_status
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
In drivers/md/dm-ioctl.c (ffffffff81d821c4)
Location: drivers/md/dm-ioctl.c:789
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:__dev_status
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
In drivers/md/dm-ioctl.c (ffffffff81e39834)
Location: drivers/md/dm-ioctl.c:789
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:__dev_status
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffff800010b06dc8)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffff800010b06dc8-ffff800010b06e48: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be58a8)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
  - drivers/md/dm-ioctl.c:dm_get_live_or_inactive_table
```
**Symbols:**

```
c0be58a8-c0be5918: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bf7ab0)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
c000000000bf7ab0-c000000000bf7b58: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f5a28)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffe0006f5a28-ffffffe0006f5aa4: dm_get_inactive_table (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff81855c20-ffffffff81855c73: dm_get_inactive_table (STB_LOCAL)
ffffffff8185807a-ffffffff8185808e: dm_get_inactive_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff8181d230-ffffffff8181d283: dm_get_inactive_table (STB_LOCAL)
ffffffff8181f68a-ffffffff8181f69e: dm_get_inactive_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff818a5250-ffffffff818a52a3: dm_get_inactive_table (STB_LOCAL)
ffffffff818a76aa-ffffffff818a76be: dm_get_inactive_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dm_table *dm_get_inactive_table(struct mapped_device *md, int *srcu_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:682
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:__dev_status
```
**Symbols:**

```
ffffffff818c1490-ffffffff818c14e3: dm_get_inactive_table (STB_LOCAL)
ffffffff818c38ea-ffffffff818c38fe: dm_get_inactive_table.cold (STB_LOCAL)
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
