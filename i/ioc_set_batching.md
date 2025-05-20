# Function: <code>ioc_set_batching</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ioc_set_batching(struct request_queue *q, struct io_context *ioc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b6060)
Location: block/blk-core.c:926
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813b6060-ffffffff813b60a0: ioc_set_batching (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ioc_set_batching(struct request_queue *q, struct io_context *ioc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813faeb0)
Location: block/blk-core.c:936
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813faeb0-ffffffff813faef0: ioc_set_batching (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ioc_set_batching(struct request_queue *q, struct io_context *ioc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814147f0)
Location: block/blk-core.c:938
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff814147f0-ffffffff81414830: ioc_set_batching (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ioc_set_batching(struct request_queue *q, struct io_context *ioc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422340)
Location: block/blk-core.c:1062
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff81422340-ffffffff81422390: ioc_set_batching (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ioc_set_batching(struct request_queue *q, struct io_context *ioc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d420)
Location: block/blk-core.c:1140
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff8144d420-ffffffff8144d470: ioc_set_batching (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ioc_set_batching(struct request_queue *q, struct io_context *ioc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814806a0)
Location: block/blk-core.c:1245
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff814806a0-ffffffff814806e0: ioc_set_batching (STB_LOCAL)
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
