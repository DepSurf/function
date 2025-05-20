# Function: <code>blk_update_bidi_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool blk_update_bidi_request(struct request *rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba4b0)
Location: block/blk-core.c:2682
Inline: True
Direct callers:
  - block/blk-core.c:blk_end_bidi_request
  - block/blk-core.c:__blk_end_bidi_request
```
**Symbols:**

```
ffffffff813ba4b0-ffffffff813ba538: blk_update_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_update_bidi_request(struct request *rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe260)
Location: block/blk-core.c:2654
Inline: True
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
```
**Symbols:**

```
ffffffff813fe260-ffffffff813fe2d0: blk_update_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool blk_update_bidi_request(struct request *rq, int error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417c00)
Location: block/blk-core.c:2645
Inline: True
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
```
**Symbols:**

```
ffffffff81417c00-ffffffff81417c70: blk_update_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_update_bidi_request(struct request *rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814259b0)
Location: block/blk-core.c:2786
Inline: True
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
```
**Symbols:**

```
ffffffff814259b0-ffffffff81425a25: blk_update_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_update_bidi_request(struct request *rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450b40)
Location: block/blk-core.c:3010
Inline: True
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
```
**Symbols:**

```
ffffffff81450b40-ffffffff81450bb3: blk_update_bidi_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool blk_update_bidi_request(struct request *rq, blk_status_t error, unsigned int nr_bytes, unsigned int bidi_bytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483df0)
Location: block/blk-core.c:3154
Inline: True
Direct callers:
  - block/blk-core.c:__blk_end_bidi_request
  - block/blk-core.c:blk_end_bidi_request
```
**Symbols:**

```
ffffffff81483df0-ffffffff81483e62: blk_update_bidi_request (STB_LOCAL)
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
