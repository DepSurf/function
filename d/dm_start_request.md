# Function: <code>dm_start_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dm_start_request(struct mapped_device *md, struct request *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a3bd0)
Location: drivers/md/dm.c:2004
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_request_fn
  - drivers/md/dm.c:dm_mq_queue_rq
  - drivers/md/dm.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff816a3bd0-ffffffff816a3ce3: dm_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dm_start_request(struct mapped_device *md, struct request *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170eed0)
Location: drivers/md/dm-rq.c:673
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff8170eed0-ffffffff8170eff8: dm_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dm_start_request(struct mapped_device *md, struct request *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81740f20)
Location: drivers/md/dm-rq.c:686
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81740f20-ffffffff81741024: dm_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dm_start_request(struct mapped_device *md, struct request *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175aae0)
Location: drivers/md/dm-rq.c:519
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff8175aae0-ffffffff8175abcc: dm_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_start_request(struct mapped_device *md, struct request *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817ccd10)
Location: drivers/md/dm-rq.c:516
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff817ccd10-ffffffff817ccdfa: dm_start_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_start_request(struct mapped_device *md, struct request *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81815ad0)
Location: drivers/md/dm-rq.c:533
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_old_request_fn
```
**Symbols:**

```
ffffffff81815ad0-ffffffff81815bb3: dm_start_request (STB_LOCAL)
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
In drivers/md/dm-rq.c (ffffffff81841c16)
Location: drivers/md/dm-rq.c:428
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81884a47)
Location: drivers/md/dm-rq.c:447
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff818b6be1)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff819874a0)
Location: drivers/md/dm-rq.c:441
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff8198b440)
Location: drivers/md/dm-rq.c:442
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff8196fb30)
Location: drivers/md/dm-rq.c:442
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81a1846d)
Location: drivers/md/dm-rq.c:442
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81b8117d)
Location: drivers/md/dm-rq.c:430
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81d1f4ad)
Location: drivers/md/dm-rq.c:431
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81d8868d)
Location: drivers/md/dm-rq.c:433
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81e3fd9d)
Location: drivers/md/dm-rq.c:433
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffff800010b0ec20)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (c0bed00c)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (c000000000c01e08)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffe0006fbe68)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff8185ca61)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81824031)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff818ac091)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff818c82e1)
Location: drivers/md/dm-rq.c:448
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
