# Function: <code>blk_end_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool blk_end_request(struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba810)
Location: block/blk-core.c:2824
Inline: True
Inline callers:
  - block/blk-core.c:blk_end_request_cur
  - block/blk-core.c:blk_end_request_err
```
**Symbols:**

```
ffffffff813ba810-ffffffff813ba822: blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool blk_end_request(struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe62e)
Location: block/blk-core.c:2796
Inline: True
Inline callers:
  - block/blk-core.c:blk_end_request_err
  - block/blk-core.c:blk_end_request_cur
```
**Symbols:**

```
ffffffff813fe590-ffffffff813fe5a2: blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool blk_end_request(struct request *rq, int error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141800e)
Location: block/blk-core.c:2793
Inline: True
Inline callers:
  - block/blk-core.c:blk_end_request_err
  - block/blk-core.c:blk_end_request_cur
```
**Symbols:**

```
ffffffff81417f70-ffffffff81417f82: blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool blk_end_request(struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425d70)
Location: block/blk-core.c:2939
Inline: False
```
**Symbols:**

```
ffffffff81425d70-ffffffff81425da3: blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool blk_end_request(struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450ee0)
Location: block/blk-core.c:3163
Inline: False
```
**Symbols:**

```
ffffffff81450ee0-ffffffff81450f13: blk_end_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_end_request(struct request *rq, blk_status_t error, unsigned int nr_bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81484190)
Location: block/blk-core.c:3308
Inline: False
```
**Symbols:**

```
ffffffff81484190-ffffffff814841b7: blk_end_request (STB_GLOBAL)
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
