# Function: <code>dm_setup_md_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a37f0)
Location: drivers/md/dm.c:2772
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff816a37f0-ffffffff816a3af2: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817040d0)
Location: drivers/md/dm.c:1771
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817040d0-ffffffff817041bd: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81735fa0)
Location: drivers/md/dm.c:1828
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81735fa0-ffffffff8173608d: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174f400)
Location: drivers/md/dm.c:2035
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8174f400-ffffffff8174f534: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c1650)
Location: drivers/md/dm.c:2014
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817c1650-ffffffff817c175f: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2199
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8180aa73-ffffffff8180aaa6: dm_setup_md_queue.cold.59 (STB_LOCAL)
ffffffff81809d00-ffffffff81809e51: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2239
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81836a73-ffffffff81836a95: dm_setup_md_queue.cold.63 (STB_LOCAL)
ffffffff81835d70-ffffffff81835e60: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2270
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8187967f-ffffffff818796a1: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff81878900-ffffffff818789ea: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818ab480-ffffffff818ab4a2: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff818aa750-ffffffff818aa82c: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2277
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8197b651-ffffffff8197b673: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff8197aa50-ffffffff8197ab2a: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2145
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81c2812a-ffffffff81c2814c: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff8197f290-ffffffff8197f345: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2164
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81c1a2e2-ffffffff81c1a304: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff819633b0-ffffffff81963465: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2045
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d2a03e-ffffffff81d2a060: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff81a0b480-ffffffff81a0b57e: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2225
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81ef629b-ffffffff81ef62bd: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff81b73890-ffffffff81b739b2: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d104f0)
Location: drivers/md/dm.c:2303
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d104f0-ffffffff81d106d5: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d79960)
Location: drivers/md/dm.c:2338
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81d79960-ffffffff81d79b5e: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e30b00)
Location: drivers/md/dm.c:2346
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81e30b00-ffffffff81e30cfe: dm_setup_md_queue (STB_GLOBAL)
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
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b00700)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffff800010b00700-ffff800010b00804: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0be0114)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c0be0114-c0be0240: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000befbd0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000befbd0-c000000000befd10: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0be0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffe0006f0be0-ffffffe0006f0c9c: dm_setup_md_queue (STB_GLOBAL)
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
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81851300-ffffffff81851322: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff818505d0-ffffffff818506ac: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81818910-ffffffff81818932: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff81817be0-ffffffff81817cbc: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818a0930-ffffffff818a0952: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff8189fc00-ffffffff8189fcdc: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dm_setup_md_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2274
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818bcb70-ffffffff818bcb92: dm_setup_md_queue.cold (STB_LOCAL)
ffffffff818bbe60-ffffffff818bbf3c: dm_setup_md_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dm_table *t</code>
</li>
</ul>
</details>
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
