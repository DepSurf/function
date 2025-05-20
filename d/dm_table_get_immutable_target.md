# Function: <code>dm_table_get_immutable_target</code>

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
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81706310)
Location: drivers/md/dm-table.c:996
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81706310-ffffffff8170633d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81738180)
Location: drivers/md/dm-table.c:997
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81738180-ffffffff817381ad: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817516e0)
Location: drivers/md/dm-table.c:1037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff817516e0-ffffffff8175170f: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c38d0)
Location: drivers/md/dm-table.c:1039
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff817c38d0-ffffffff817c38ff: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180c5b9)
Location: drivers/md/dm-table.c:1074
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff8180c370-ffffffff8180c39d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81838553)
Location: drivers/md/dm-table.c:1059
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81838330-ffffffff8183835d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187b12a)
Location: drivers/md/dm-table.c:1072
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8187af10-ffffffff8187af3d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818acf1a)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff818acd00-ffffffff818acd2d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197d21c)
Location: drivers/md/dm-table.c:1046
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8197d410-ffffffff8197d43d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81981843)
Location: drivers/md/dm-table.c:991
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81981990-ffffffff819819bd: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81965a83)
Location: drivers/md/dm-table.c:977
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81965bd0-ffffffff81965bfd: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0da13)
Location: drivers/md/dm-table.c:972
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81a0db60-ffffffff81a0db8d: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b74dbc)
Location: drivers/md/dm-table.c:974
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81b76280-ffffffff81b762b5: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d11e64)
Location: drivers/md/dm-table.c:969
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81d13650-ffffffff81d13685: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b234)
Location: drivers/md/dm-table.c:963
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81d7c7b0-ffffffff81d7c7e5: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e321b4)
Location: drivers/md/dm-table.c:985
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_determine_type
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81e33c90-ffffffff81e33cc5: dm_table_get_immutable_target (STB_GLOBAL)
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
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b039cc)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffff800010b03758-ffff800010b037ac: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be2a58)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
c0be2810-c0be2858: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf3050)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
c000000000bf2d70-c000000000bf2da8: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f2ea2)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffe0006f2c86-ffffffe0006f2cbe: dm_table_get_immutable_target (STB_GLOBAL)
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
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81852d9a)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff81852b80-ffffffff81852bad: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181a3aa)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff8181a190-ffffffff8181a1bd: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a23ca)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff818a21b0-ffffffff818a21dd: dm_table_get_immutable_target (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dm_target *dm_table_get_immutable_target(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818be60a)
Location: drivers/md/dm-table.c:1070
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
**Symbols:**

```
ffffffff818be3f0-ffffffff818be41d: dm_table_get_immutable_target (STB_GLOBAL)
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
