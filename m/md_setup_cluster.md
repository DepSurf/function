# Function: <code>md_setup_cluster</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81697c60)
Location: drivers/md/md.c:7571
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81697c60-ffffffff81697cfa: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f8750)
Location: drivers/md/md.c:7611
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff816f8750-ffffffff816f87e8: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81729f70)
Location: drivers/md/md.c:7668
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81729f70-ffffffff8172a008: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817427d0)
Location: drivers/md/md.c:7889
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff817427d0-ffffffff8174286b: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b48e0)
Location: drivers/md/md.c:7946
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff817b48e0-ffffffff817b4981: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8015
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff81800b9d-ffffffff81800bbf: md_setup_cluster.cold.88 (STB_LOCAL)
ffffffff817fb990-ffffffff817fba15: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8019
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
```
**Symbols:**

```
ffffffff8182cda0-ffffffff8182cdc2: md_setup_cluster.cold.87 (STB_LOCAL)
ffffffff81827a80-ffffffff81827b05: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8089
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff8186f370-ffffffff8186f392: md_setup_cluster.cold (STB_LOCAL)
ffffffff81869f20-ffffffff81869fa7: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818a1133-ffffffff818a1155: md_setup_cluster.cold (STB_LOCAL)
ffffffff8189bcc0-ffffffff8189bd47: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8390
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81970f2e-ffffffff81970f50: md_setup_cluster.cold (STB_LOCAL)
ffffffff8196bcf0-ffffffff8196bd77: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8418
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81c2702b-ffffffff81c2704d: md_setup_cluster.cold (STB_LOCAL)
ffffffff81972b90-ffffffff81972c23: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8376
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81c191dc-ffffffff81c191fe: md_setup_cluster.cold (STB_LOCAL)
ffffffff81956c80-ffffffff81956d13: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8389
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81d28805-ffffffff81d28827: md_setup_cluster.cold (STB_LOCAL)
ffffffff819fc350-ffffffff819fc3e3: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8391
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81ef4869-ffffffff81ef488b: md_setup_cluster.cold (STB_LOCAL)
ffffffff81b639c0-ffffffff81b63a59: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfe820)
Location: drivers/md/md.c:8402
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81cfe820-ffffffff81cfe8d0: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d65ac0)
Location: drivers/md/md.c:8411
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81d65ac0-ffffffff81d65b70: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1c840)
Location: drivers/md/md.c:8502
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81e1c840-ffffffff81e1c8f0: md_setup_cluster (STB_GLOBAL)
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
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af0328)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffff800010af0328-ffff800010af041c: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd1714)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
c0bd1714-c0bd17dc: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdc0b0)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
c000000000bdc0b0-c000000000bdc210: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e43de)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffe0006e43de-ffffffe0006e44c6: md_setup_cluster (STB_GLOBAL)
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
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81846fb3-ffffffff81846fd5: md_setup_cluster.cold (STB_LOCAL)
ffffffff81841b40-ffffffff81841bc7: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff8180e613-ffffffff8180e635: md_setup_cluster.cold (STB_LOCAL)
ffffffff818091a0-ffffffff81809227: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818965e3-ffffffff81896605: md_setup_cluster.cold (STB_LOCAL)
ffffffff81891170-ffffffff818911f7: md_setup_cluster (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int md_setup_cluster(struct mddev *mddev, int nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:8193
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818b25c3-ffffffff818b25e5: md_setup_cluster.cold (STB_LOCAL)
ffffffff818acd50-ffffffff818acdd5: md_setup_cluster (STB_GLOBAL)
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
