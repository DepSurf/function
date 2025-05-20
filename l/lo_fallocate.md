# Function: <code>lo_fallocate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172d5ec)
Location: drivers/block/loop.c:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff817e7e70)
Location: drivers/block/loop.c:432
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e7e70-ffffffff817e7ed2: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817fcd90)
Location: drivers/block/loop.c:429
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817fcd90-ffffffff817fcdf2: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff817e1820)
Location: drivers/block/loop.c:471
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff817e1820-ffffffff817e1881: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff8186cfc0)
Location: drivers/block/loop.c:461
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff8186cfc0-ffffffff8186d021: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff819b5f50)
Location: drivers/block/loop.c:309
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff819b5f50-ffffffff819b5fd8: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff81b2b0e0)
Location: drivers/block/loop.c:309
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b2b0e0-ffffffff81b2b168: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff81b7b3d0)
Location: drivers/block/loop.c:309
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81b7b3d0-ffffffff81b7b456: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff81bcf1c0)
Location: drivers/block/loop.c:305
Inline: True
Direct callers:
  - drivers/block/loop.c:do_req_filebacked
  - drivers/block/loop.c:do_req_filebacked
```
**Symbols:**

```
ffffffff81bcf1c0-ffffffff81bcf246: lo_fallocate.isra.0 (STB_LOCAL)
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
In drivers/block/loop.c (ffff800010922cb4)
Location: drivers/block/loop.c:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lo_fallocate(struct loop_device *lo, struct request *rq, loff_t pos, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a05924)
Location: drivers/block/loop.c:420
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c0a05924-c0a059ac: lo_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lo_fallocate(struct loop_device *lo, struct request *rq, loff_t pos, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c4a20)
Location: drivers/block/loop.c:420
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
c0000000009c4a20-c0000000009c4ac8: lo_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lo_fallocate(struct loop_device *lo, struct request *rq, loff_t pos, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe00059f47a)
Location: drivers/block/loop.c:420
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_queue_work
```
**Symbols:**

```
ffffffe00059f47a-ffffffe00059f4e4: lo_fallocate (STB_LOCAL)
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
In drivers/block/loop.c (ffffffff816f33cc)
Location: drivers/block/loop.c:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff816cd4cc)
Location: drivers/block/loop.c:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff81720aac)
Location: drivers/block/loop.c:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
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
In drivers/block/loop.c (ffffffff8173be6c)
Location: drivers/block/loop.c:420
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_queue_work
  - drivers/block/loop.c:loop_queue_work
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
