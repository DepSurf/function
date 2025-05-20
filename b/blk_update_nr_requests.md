# Function: <code>blk_update_nr_requests</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_update_nr_requests(struct request_queue *q, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9ef0)
Location: block/blk-core.c:970
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_requests_store
```
**Symbols:**

```
ffffffff813b9ef0-ffffffff813ba0aa: blk_update_nr_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_update_nr_requests(struct request_queue *q, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fdcb0)
Location: block/blk-core.c:980
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_requests_store
```
**Symbols:**

```
ffffffff813fdcb0-ffffffff813fde64: blk_update_nr_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_update_nr_requests(struct request_queue *q, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814175f0)
Location: block/blk-core.c:982
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_requests_store
```
**Symbols:**

```
ffffffff814175f0-ffffffff814177a4: blk_update_nr_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_update_nr_requests(struct request_queue *q, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425450)
Location: block/blk-core.c:1106
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_requests_store
```
**Symbols:**

```
ffffffff81425450-ffffffff81425600: blk_update_nr_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_update_nr_requests(struct request_queue *q, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814505f0)
Location: block/blk-core.c:1184
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_requests_store
```
**Symbols:**

```
ffffffff814505f0-ffffffff814507a0: blk_update_nr_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_update_nr_requests(struct request_queue *q, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814838e0)
Location: block/blk-core.c:1289
Inline: False
Direct callers:
  - block/blk-sysfs.c:queue_requests_store
```
**Symbols:**

```
ffffffff814838e0-ffffffff81483a96: blk_update_nr_requests (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
