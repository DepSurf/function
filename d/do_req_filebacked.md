# Function: <code>do_req_filebacked</code>

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
In drivers/block/loop.c (ffffffff815706da)
Location: drivers/block/loop.c:531
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c627f)
Location: drivers/block/loop.c:513
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f47cd)
Location: drivers/block/loop.c:513
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81608a6f)
Location: drivers/block/loop.c:508
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8167130f)
Location: drivers/block/loop.c:556
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816ace2b)
Location: drivers/block/loop.c:582
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cd17c)
Location: drivers/block/loop.c:582
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff817092ad)
Location: drivers/block/loop.c:582
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8172d5ae)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e9140)
Location: drivers/block/loop.c:597
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff817e9140-ffffffff817e9424: do_req_filebacked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fdd70)
Location: drivers/block/loop.c:595
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff817fdd70-ffffffff817fdea5: do_req_filebacked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e2790)
Location: drivers/block/loop.c:637
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff817e2790-ffffffff817e2a52: do_req_filebacked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:622
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff8186eb70-ffffffff8186ee53: do_req_filebacked (STB_LOCAL)
ffffffff81d058e9-ffffffff81d05921: do_req_filebacked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:463
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff819b73c0-ffffffff819b7531: do_req_filebacked (STB_LOCAL)
ffffffff81ece293-ffffffff81ece2cd: do_req_filebacked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:463
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff81b2c6b0-ffffffff81b2c821: do_req_filebacked (STB_LOCAL)
ffffffff82099ad0-ffffffff82099b0a: do_req_filebacked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:463
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff81b7c900-ffffffff81b7ca9b: do_req_filebacked (STB_LOCAL)
ffffffff8211ab7f-ffffffff8211abb9: do_req_filebacked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_req_filebacked(struct loop_device *lo, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:459
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
  - drivers/block/loop.c:loop_process_work
```
**Symbols:**

```
ffffffff81bd0840-ffffffff81bd09db: do_req_filebacked (STB_LOCAL)
ffffffff821f8a05-ffffffff821f8a3f: do_req_filebacked.cold (STB_LOCAL)
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
In drivers/block/loop.c (ffff800010922c7c)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (c0a08990)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (c0000000009c9014)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffe0005a1e7e)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816f338e)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cd48e)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81720a6e)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8173be2e)
Location: drivers/block/loop.c:584
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
