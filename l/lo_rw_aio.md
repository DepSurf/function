# Function: <code>lo_rw_aio</code>

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
In drivers/block/loop.c (ffffffff815710b1)
Location: drivers/block/loop.c:476
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c5f50)
Location: drivers/block/loop.c:476
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff815c5f50-ffffffff815c61c4: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f44b0)
Location: drivers/block/loop.c:476
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff815f44b0-ffffffff815f473a: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816087e0)
Location: drivers/block/loop.c:471
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816087e0-ffffffff816089df: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816703e0)
Location: drivers/block/loop.c:485
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816703e0-ffffffff81670877: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ac900)
Location: drivers/block/loop.c:509
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816ac900-ffffffff816acdd1: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ccc60)
Location: drivers/block/loop.c:510
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816ccc60-ffffffff816cd12e: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817082a0)
Location: drivers/block/loop.c:510
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff817082a0-ffffffff8170863f: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172c4f0)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8172c4f0-ffffffff8172c88f: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff817e8ad0)
Location: drivers/block/loop.c:525
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e8ad0-ffffffff817e8e51: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff817fdab0)
Location: drivers/block/loop.c:523
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817fdab0-ffffffff817fdd64: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff817e2210)
Location: drivers/block/loop.c:565
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e2210-ffffffff817e24c4: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff8186e610)
Location: drivers/block/loop.c:553
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff8186e610-ffffffff8186e8ac: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff819b6ec0)
Location: drivers/block/loop.c:394
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff819b6ec0-ffffffff819b71a9: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2c170)
Location: drivers/block/loop.c:394
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b2c170-ffffffff81b2c461: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7c450)
Location: drivers/block/loop.c:394
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b7c450-ffffffff81b7c700: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd0380)
Location: drivers/block/loop.c:390
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81bd0380-ffffffff81bd0630: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (ffff800010922350)
Location: drivers/block/loop.c:512
Inline: True
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffff800010922350-ffff800010922700: lo_rw_aio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a084b4)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c0a084b4-c0a08930: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c7b00)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c0000000009c7b00-c0000000009c8010: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a11a6)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffe0005a11a6-ffffffe0005a14c8: lo_rw_aio (STB_LOCAL)
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
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816f22d0)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816f22d0-ffffffff816f266f: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cc3d0)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff816cc3d0-ffffffff816cc76f: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171f9b0)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8171f9b0-ffffffff8171fd4f: lo_rw_aio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device *lo, struct loop_cmd *cmd, loff_t pos, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8173ad70)
Location: drivers/block/loop.c:512
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffff8173ad70-ffffffff8173b10f: lo_rw_aio (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
