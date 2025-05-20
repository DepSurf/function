# Function: <code>blk_end_bidi_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_end_bidi_request(struct request *rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba7b0)
Location: block/blk-core.c:2768
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_end_request_err
```
**Symbols:**

```
ffffffff813ba7b0-ffffffff813ba80f: blk_end_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_end_bidi_request(struct request *rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe530)
Location: block/blk-core.c:2740
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_request_err
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
```
**Symbols:**

```
ffffffff813fe530-ffffffff813fe58e: blk_end_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_end_bidi_request(struct request *rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417f10)
Location: block/blk-core.c:2737
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_request_err
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_end_request_cur
```
**Symbols:**

```
ffffffff81417f10-ffffffff81417f6e: blk_end_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_end_bidi_request(struct request *rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425cf0)
Location: block/blk-core.c:2878
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_request
  - block/blk-core.c:blk_end_request
```
**Symbols:**

```
ffffffff81425cf0-ffffffff81425d61: blk_end_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_end_bidi_request(struct request *rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450e60)
Location: block/blk-core.c:3102
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_request
  - block/blk-core.c:blk_end_request
```
**Symbols:**

```
ffffffff81450e60-ffffffff81450ed1: blk_end_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_end_bidi_request(struct request *rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484120)
Location: block/blk-core.c:3247
Inline: False
Direct callers:
  - block/blk-core.c:blk_end_request
```
**Symbols:**

```
ffffffff81484120-ffffffff81484190: blk_end_bidi_request (STB_LOCAL)
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
