# Function: <code>blkg_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d83f0)
Location: block/blk-cgroup.c:308
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_destroy_all
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff813d83f0-ffffffff813d85a7: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141e120)
Location: block/blk-cgroup.c:308
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff8141e120-ffffffff8141e2e2: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814396e0)
Location: block/blk-cgroup.c:309
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff814396e0-ffffffff814398a2: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81446ef0)
Location: block/blk-cgroup.c:310
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff81446ef0-ffffffff81447039: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81473ad0)
Location: block/blk-cgroup.c:310
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_css_offline
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff81473ad0-ffffffff81473c1c: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a7ea0)
Location: block/blk-cgroup.c:328
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_css_free
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff814a7ea0-ffffffff814a80ad: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1b20)
Location: block/blk-cgroup.c:372
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff814c1b20-ffffffff814c1d2b: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f01e0)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff814f01e0-ffffffff814f03e3: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81509690)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff81509690-ffffffff81509890: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81569b90)
Location: block/blk-cgroup.c:396
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff81569b90-ffffffff81569c87: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815844a0)
Location: block/blk-cgroup.c:377
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff815844a0-ffffffff81584597: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158b2a0)
Location: block/blk-cgroup.c:375
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff8158b2a0-ffffffff8158b397: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f02a0)
Location: block/blk-cgroup.c:378
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff815f02a0-ffffffff815f0416: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a14f0)
Location: block/blk-cgroup.c:439
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_unpin_online
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff816a14f0-ffffffff816a1672: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81760360)
Location: block/blk-cgroup.c:453
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
**Symbols:**

```
ffffffff81760360-ffffffff817604e2: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.c:528
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
**Symbols:**

```
ffffffff8179f6c0-ffffffff8179f87f: blkg_destroy (STB_LOCAL)
ffffffff820f6a98-ffffffff820f6ab5: blkg_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (0)
Location: block/blk-cgroup.c:528
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
**Symbols:**

```
ffffffff817e3190-ffffffff817e334f: blkg_destroy (STB_LOCAL)
ffffffff821d3ee6-ffffffff821d3f03: blkg_destroy.cold (STB_LOCAL)
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
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060c460)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffff80001060c460-ffff80001060c678: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b7b54)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
c07b7b54-c07b7e28: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007a9260)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
c0000000007a9260-c0000000007a94f8: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe000444f64)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffe000444f64-ffffffe0004450ec: blkg_destroy (STB_LOCAL)
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
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81501c70)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff81501c70-ffffffff81501e70: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f2180)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff814f2180-ffffffff814f2380: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fdd00)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff814fdd00-ffffffff814fdf00: blkg_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkg_destroy(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815174e0)
Location: block/blk-cgroup.c:393
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_destroy_blkgs
  - block/blk-cgroup.c:blkg_destroy_all
```
**Symbols:**

```
ffffffff815174e0-ffffffff815176e0: blkg_destroy (STB_LOCAL)
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
