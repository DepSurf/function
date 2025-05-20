# Function: <code>blk_cgroup_bio_start</code>

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
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586e50)
Location: block/blk-cgroup.c:1904
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff81586e50-ffffffff81586ebd: blk_cgroup_bio_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158dc90)
Location: block/blk-cgroup.c:1913
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff8158dc90-ffffffff8158dd08: blk_cgroup_bio_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f3700)
Location: block/blk-cgroup.c:1907
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_checks
```
**Symbols:**

```
ffffffff815f3700-ffffffff815f37ea: blk_cgroup_bio_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a4d30)
Location: block/blk-cgroup.c:1991
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
```
**Symbols:**

```
ffffffff816a4d30-ffffffff816a4e60: blk_cgroup_bio_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81763af0)
Location: block/blk-cgroup.c:1997
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
**Symbols:**

```
ffffffff81763af0-ffffffff81763c80: blk_cgroup_bio_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a2b90)
Location: block/blk-cgroup.c:2088
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
**Symbols:**

```
ffffffff817a2b90-ffffffff817a2ce4: blk_cgroup_bio_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_cgroup_bio_start(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e66d0)
Location: block/blk-cgroup.c:2104
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
**Symbols:**

```
ffffffff817e66d0-ffffffff817e6824: blk_cgroup_bio_start (STB_GLOBAL)
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
