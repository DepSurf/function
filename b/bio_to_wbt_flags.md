# Function: <code>bio_to_wbt_flags</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd2c5)
Location: block/blk-wbt.c:544
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff814cd250-ffffffff814cd2b8: bio_to_wbt_flags.isra.21.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814fbb55)
Location: block/blk-wbt.c:545
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff814fbae0-ffffffff814fbb49: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81519985)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff81519910-ffffffff81519979: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81579f95)
Location: block/blk-wbt.c:539
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff81579e60-ffffffff81579eca: bio_to_wbt_flags.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81596ea5)
Location: block/blk-wbt.c:539
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff81596d70-ffffffff81596dda: bio_to_wbt_flags.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum wbt_flags bio_to_wbt_flags(struct rq_wb *rwb, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159db40)
Location: block/blk-wbt.c:540
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff8159db40-ffffffff8159dbbd: bio_to_wbt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum wbt_flags bio_to_wbt_flags(struct rq_wb *rwb, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81606220)
Location: block/blk-wbt.c:543
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff81606220-ffffffff8160629d: bio_to_wbt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum wbt_flags bio_to_wbt_flags(struct rq_wb *rwb, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816b9ee0)
Location: block/blk-wbt.c:543
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff816b9ee0-ffffffff816b9f69: bio_to_wbt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum wbt_flags bio_to_wbt_flags(struct rq_wb *rwb, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a3f0)
Location: block/blk-wbt.c:557
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff8177a3f0-ffffffff8177a479: bio_to_wbt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum wbt_flags bio_to_wbt_flags(struct rq_wb *rwb, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba1e0)
Location: block/blk-wbt.c:616
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff817ba1e0-ffffffff817ba26a: bio_to_wbt_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum wbt_flags bio_to_wbt_flags(struct rq_wb *rwb, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fe950)
Location: block/blk-wbt.c:615
Inline: True
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff817fe950-ffffffff817fe9da: bio_to_wbt_flags (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffff800010620f54)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffff800010620e90-ffff800010620f30: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (c07c8fe4)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
c07c8f40-c07c8fd0: bio_to_wbt_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (c0000000007c13f8)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
c0000000007c1350-c0000000007c13d8: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffe000453a04)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffe000453970-ffffffe0004539e6: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81511f65)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff81511ef0-ffffffff81511f59: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81502285)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff81502210-ffffffff81502279: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff8150dff5)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff8150df80-ffffffff8150dfe9: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81527615)
Location: block/blk-wbt.c:547
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
Direct callers:
  - block/blk-wbt.c:wbt_track
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_cleanup
```
**Symbols:**

```
ffffffff815275a0-ffffffff81527609: bio_to_wbt_flags.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
