# Function: <code>bd_clear_claiming</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8131393e)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffff813132a0-ffffffff813132ab: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8132684e)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffff813261c0-ffffffff813261cb: bd_clear_claiming.part.0 (STB_LOCAL)
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
In fs/block_dev.c (ffffffff813615bf)
Location: fs/block_dev.c:1172
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:blkdev_get
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_finish_claiming
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
In fs/block_dev.c (ffffffff8136daaa)
Location: fs/block_dev.c:1040
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
  - fs/block_dev.c:bd_finish_claiming
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
In fs/block_dev.c (ffffffff8137448a)
Location: fs/block_dev.c:1046
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_abort_claiming
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
In block/bdev.c (ffffffff815c4572)
Location: block/bdev.c:602
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
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
In block/bdev.c (ffffffff8166ef49)
Location: block/bdev.c:607
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
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
In block/bdev.c (ffffffff8172a239)
Location: block/bdev.c:606
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
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
In block/bdev.c (ffffffff81766585)
Location: block/bdev.c:551
Inline: True
Inline callers:
  - block/bdev.c:truncate_bdev_range
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
In block/bdev.c (ffffffff817a89e8)
Location: block/bdev.c:542
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:truncate_bdev_range
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
In fs/block_dev.c (ffff8000103e12d0)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffff8000103e0488-ffff8000103e049c: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (c05b93b4)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
```
**Symbols:**

```
c05b929c-c05b92b4: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bd_clear_claiming(struct block_device *whole, void *holder);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e5250)
Location: fs/block_dev.c:1191
Inline: False
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
  - fs/block_dev.c:bd_finish_claiming
```
**Symbols:**

```
c0000000004e5250-c0000000004e52a8: bd_clear_claiming (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffe000297afa)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffe00029721c-ffffffe000297230: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8131ee2e)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffff8131e7a0-ffffffff8131e7ab: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8130f9ce)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffff8130f340-ffffffff8130f34b: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8131c8fe)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffff8131c270-ffffffff8131c27b: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8132e3ae)
Location: fs/block_dev.c:1191
Inline: True
Inline callers:
  - fs/block_dev.c:bd_abort_claiming
Direct callers:
  - fs/block_dev.c:bd_abort_claiming
```
**Symbols:**

```
ffffffff8132e380-ffffffff8132e38b: bd_clear_claiming.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
