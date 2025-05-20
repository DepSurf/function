# Function: <code>hd_struct_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813ba66f)
Location: include/linux/genhd.h:674
Inline: True
```
```
In block/blk-merge.c (ffffffff813c194d)
Location: include/linux/genhd.h:674
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fe3d7)
Location: include/linux/genhd.h:663
Inline: True
```
```
In block/blk-merge.c (ffffffff81405883)
Location: include/linux/genhd.h:663
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417d6e)
Location: include/linux/genhd.h:654
Inline: True
```
```
In block/blk-merge.c (ffffffff8141faf8)
Location: include/linux/genhd.h:654
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81425b68)
Location: include/linux/genhd.h:648
Inline: True
```
```
In block/blk-merge.c (ffffffff8142d991)
Location: include/linux/genhd.h:648
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81450cd8)
Location: include/linux/genhd.h:657
Inline: True
```
```
In block/blk-merge.c (ffffffff81458bc0)
Location: include/linux/genhd.h:657
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483f73)
Location: include/linux/genhd.h:666
Inline: True
```
```
In block/blk-merge.c (ffffffff8148bcde)
Location: include/linux/genhd.h:666
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149f53e)
Location: include/linux/genhd.h:689
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814a5977)
Location: include/linux/genhd.h:689
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd63b)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814d3983)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e692b)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814eccb3)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81545ea1)
Location: block/blk.h:371
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff8154aebc)
Location: block/blk.h:371
Inline: True
Inline callers:
  - block/blk-merge.c:blk_account_io_merge_request
```
</details>
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e40f8)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffff8000105eb698)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c079141c)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (c0797c54)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000777dd8)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (c000000000780cd0)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004259fe)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffe00042b718)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814def0b)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814e5293)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cf8ab)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814d5942)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814daf9b)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814e1323)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f3d37)
Location: include/linux/genhd.h:697
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_done
```
```
In block/blk-merge.c (ffffffff814fa1af)
Location: include/linux/genhd.h:697
Inline: True
```
</details>
</li>
</ul>

## Differences
