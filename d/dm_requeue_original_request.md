# Function: <code>dm_requeue_original_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_requeue_original_request(struct mapped_device *md, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1a90)
Location: drivers/md/dm.c:1212
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:map_request
  - drivers/md/dm.c:map_tio_request
```
**Symbols:**

```
ffffffff816a1a90-ffffffff816a1bba: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_requeue_original_request(struct mapped_device *md, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170f070)
Location: drivers/md/dm-rq.c:334
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_tio_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff8170f070-ffffffff8170f1d4: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817410a0)
Location: drivers/md/dm-rq.c:342
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_tio_request
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff817410a0-ffffffff817411eb: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175ad50)
Location: drivers/md/dm-rq.c:268
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_tio_request
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8175ad50-ffffffff8175ae3a: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817ccf80)
Location: drivers/md/dm-rq.c:263
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_tio_request
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff817ccf80-ffffffff817cd080: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81815d40)
Location: drivers/md/dm-rq.c:263
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_tio_request
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81815d40-ffffffff81815e40: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81841b10)
Location: drivers/md/dm-rq.c:179
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81841b10-ffffffff81841ba3: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81884940)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81884940-ffffffff818849d3: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b6830)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff818b6830-ffffffff818b68c3: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff819870b0)
Location: drivers/md/dm-rq.c:188
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff819870b0-ffffffff81987182: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b090)
Location: drivers/md/dm-rq.c:188
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8198b090-ffffffff8198b162: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196f780)
Location: drivers/md/dm-rq.c:188
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8196f780-ffffffff8196f851: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a180c0)
Location: drivers/md/dm-rq.c:188
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81a180c0-ffffffff81a18191: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b80de0)
Location: drivers/md/dm-rq.c:187
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81b80de0-ffffffff81b80ec5: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1f0e0)
Location: drivers/md/dm-rq.c:186
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81d1f0e0-ffffffff81d1f1c5: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d882c0)
Location: drivers/md/dm-rq.c:188
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81d882c0-ffffffff81d883a5: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3f9d0)
Location: drivers/md/dm-rq.c:188
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81e3f9d0-ffffffff81e3fab5: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0e870)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffff800010b0e870-ffff800010b0e918: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0becc50)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c0becc50-c0becce8: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c018f0)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
c000000000c018f0-c000000000c019d0: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fbb70)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffe0006fbb70-ffffffe0006fbc0e: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185c6b0)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff8185c6b0-ffffffff8185c743: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81823c80)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff81823c80-ffffffff81823d13: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818abce0)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff818abce0-ffffffff818abd73: dm_requeue_original_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dm_requeue_original_request(struct dm_rq_target_io *tio, bool delay_requeue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c7f20)
Location: drivers/md/dm-rq.c:195
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:map_request
```
**Symbols:**

```
ffffffff818c7f20-ffffffff818c7fb3: dm_requeue_original_request (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dm_rq_target_io *tio</code>
</li>
<li>
<b>Param added. </b>
<code>bool delay_requeue</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mapped_device *md</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request *rq</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
