# Function: <code>__blk_mq_complete_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4120)
Location: block/blk-mq.c:359
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff813c4120-ffffffff813c41fa: __blk_mq_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81407850)
Location: block/blk-mq.c:415
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff81407850-ffffffff8140791f: __blk_mq_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81422420)
Location: block/blk-mq.c:427
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff81422420-ffffffff81422542: __blk_mq_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f7e0)
Location: block/blk-mq.c:487
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff8142f7e0-ffffffff8142f914: __blk_mq_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_mq_complete_request(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145ad60)
Location: block/blk-mq.c:529
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_complete_request
```
**Symbols:**

```
ffffffff8145ad60-ffffffff8145aea0: __blk_mq_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148dde5)
Location: block/blk-mq.c:557
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7675)
Location: block/blk-mq.c:576
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d56e5)
Location: block/blk-mq.c:571
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee9c5)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ede44)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799b80)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007835b4)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cfa8)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6fa5)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7515)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e3035)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbeb5)
Location: block/blk-mq.c:582
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_complete_request
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
</ul>
