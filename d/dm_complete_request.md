# Function: <code>dm_complete_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a10c8)
Location: drivers/md/dm.c:1334
Inline: True
Inline callers:
  - drivers/md/dm.c:end_clone_request
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:dm_request_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_complete_request(struct request *rq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170ecb0)
Location: drivers/md/dm-rq.c:416
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff8170ecb0-ffffffff8170ecf6: dm_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_complete_request(struct request *rq, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81740ce0)
Location: drivers/md/dm-rq.c:425
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81740ce0-ffffffff81740d26: dm_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_complete_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175abd0)
Location: drivers/md/dm-rq.c:361
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff8175abd0-ffffffff8175abfc: dm_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_complete_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cce00)
Location: drivers/md/dm-rq.c:357
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff817cce00-ffffffff817cce2c: dm_complete_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_complete_request(struct request *rq, blk_status_t error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81815bc0)
Location: drivers/md/dm-rq.c:361
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
**Symbols:**

```
ffffffff81815bc0-ffffffff81815beb: dm_complete_request (STB_LOCAL)
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
In drivers/md/dm-rq.c (ffffffff81841cda)
Location: drivers/md/dm-rq.c:267
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffff81884b4f)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffff818b6b43)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81987403)
Location: drivers/md/dm-rq.c:279
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b3a7)
Location: drivers/md/dm-rq.c:279
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196fa97)
Location: drivers/md/dm-rq.c:279
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a183d7)
Location: drivers/md/dm-rq.c:279
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b80fc1)
Location: drivers/md/dm-rq.c:275
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1f265)
Location: drivers/md/dm-rq.c:274
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d88446)
Location: drivers/md/dm-rq.c:276
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3fb56)
Location: drivers/md/dm-rq.c:276
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
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
In drivers/md/dm-rq.c (ffff800010b0eb5c)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (c0becedc)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (c000000000c01d20)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffe0006fbd9e)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffff8185c9c3)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffff81823f93)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffff818abff3)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
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
In drivers/md/dm-rq.c (ffffffff818c824a)
Location: drivers/md/dm-rq.c:286
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:end_clone_request
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
