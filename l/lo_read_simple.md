# Function: <code>lo_read_simple</code>

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
In drivers/block/loop.c (ffffffff81570d55)
Location: drivers/block/loop.c:335
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
In drivers/block/loop.c (ffffffff815c6522)
Location: drivers/block/loop.c:335
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
In drivers/block/loop.c (ffffffff815f4e00)
Location: drivers/block/loop.c:335
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
In drivers/block/loop.c (ffffffff81608eae)
Location: drivers/block/loop.c:335
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
In drivers/block/loop.c (ffffffff81671777)
Location: drivers/block/loop.c:338
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
In drivers/block/loop.c (ffffffff816acf19)
Location: drivers/block/loop.c:340
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
In drivers/block/loop.c (ffffffff816cd352)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffff81709507)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffff8172d82d)
Location: drivers/block/loop.c:341
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
int lo_read_simple(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e88f0)
Location: drivers/block/loop.c:353
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e88f0-ffffffff817e8ac6: lo_read_simple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lo_read_simple(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fd770)
Location: drivers/block/loop.c:350
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817fd770-ffffffff817fd903: lo_read_simple (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817e2901)
Location: drivers/block/loop.c:392
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
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
In drivers/block/loop.c (ffffffff8186ecff)
Location: drivers/block/loop.c:382
Inline: True
Inline callers:
  - drivers/block/loop.c:do_req_filebacked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lo_read_simple(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b71b0)
Location: drivers/block/loop.c:280
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff819b71b0-ffffffff819b73b2: lo_read_simple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lo_read_simple(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2c480)
Location: drivers/block/loop.c:280
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b2c480-ffffffff81b2c694: lo_read_simple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lo_read_simple(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7c710)
Location: drivers/block/loop.c:280
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b7c710-ffffffff81b7c8e5: lo_read_simple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lo_read_simple(struct loop_device *lo, struct request *rq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd0640)
Location: drivers/block/loop.c:276
Inline: False
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81bd0640-ffffffff81bd0825: lo_read_simple (STB_LOCAL)
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
In drivers/block/loop.c (ffff800010922e48)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (c0a08a60)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (c0000000009c9360)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffe0005a2034)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffff816f360d)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffff816cd70d)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffff81720ced)
Location: drivers/block/loop.c:341
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
In drivers/block/loop.c (ffffffff8173c09f)
Location: drivers/block/loop.c:341
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
