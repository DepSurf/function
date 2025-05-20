# Function: <code>__blk_end_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool __blk_end_request(struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813bb080)
Location: block/blk-core.c:2901
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-core.c:__blk_end_request_err
```
**Symbols:**

```
ffffffff813bb080-ffffffff813bb092: __blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool __blk_end_request(struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813feede)
Location: block/blk-core.c:2873
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_err
  - block/blk-core.c:__blk_end_request_cur
```
**Symbols:**

```
ffffffff813fee40-ffffffff813fee52: __blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool __blk_end_request(struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141890e)
Location: block/blk-core.c:2870
Inline: True
Inline callers:
  - block/blk-core.c:__blk_end_request_err
  - block/blk-core.c:__blk_end_request_cur
```
**Symbols:**

```
ffffffff81418870-ffffffff81418882: __blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __blk_end_request(struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425e40)
Location: block/blk-core.c:2981
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-flush.c:blk_insert_flush
```
**Symbols:**

```
ffffffff81425e40-ffffffff81425e73: __blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __blk_end_request(struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450fb0)
Location: block/blk-core.c:3205
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-flush.c:blk_insert_flush
```
**Symbols:**

```
ffffffff81450fb0-ffffffff81450fe3: __blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __blk_end_request(struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484240)
Location: block/blk-core.c:3350
Inline: False
Direct callers:
  - block/blk-core.c:__blk_end_request_cur
  - block/blk-flush.c:blk_insert_flush
```
**Symbols:**

```
ffffffff81484240-ffffffff81484267: __blk_end_request (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int error</code> ➡️ <code>blk_status_t error</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
