# Function: <code>__blk_throtl_bio</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __blk_throtl_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816aa980)
Location: block/blk-throttle.c:2091
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
```
**Symbols:**

```
ffffffff816aa980-ffffffff816aaf6b: __blk_throtl_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __blk_throtl_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81769420)
Location: block/blk-throttle.c:2165
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
```
**Symbols:**

```
ffffffff81769420-ffffffff81769922: __blk_throtl_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __blk_throtl_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a85e0)
Location: block/blk-throttle.c:2168
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
```
**Symbols:**

```
ffffffff817a85e0-ffffffff817a89c3: __blk_throtl_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __blk_throtl_bio(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817ec350)
Location: block/blk-throttle.c:2176
Inline: False
Direct callers:
  - block/blk-core.c:submit_bio_noacct
```
**Symbols:**

```
ffffffff817ec350-ffffffff817ec730: __blk_throtl_bio (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
