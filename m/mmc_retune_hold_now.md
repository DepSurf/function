# Function: <code>mmc_retune_hold_now</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e85b7)
Location: drivers/mmc/core/host.h:27
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
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
In drivers/mmc/core/core.c (ffffffff81834205)
Location: drivers/mmc/core/host.h:27
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
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
In drivers/mmc/core/core.c (ffffffff81860195)
Location: drivers/mmc/core/host.h:27
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
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
In drivers/mmc/core/core.c (ffffffff818a3de0)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818af7fc)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
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
In drivers/mmc/core/core.c (ffffffff818d62eb)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818e1cac)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
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
In drivers/mmc/core/core.c (ffffffff819a8c3f)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b4cac)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81c2a070)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff819b725c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81c1c48c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8199ba1c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d2ce73)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81a483cc)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ef9237)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81bb643c)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d484e5)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81d5ae5c)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db2de5)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81dc58dc)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6b175)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7b9dc)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
```
```
In drivers/mmc/core/sdio_io.c (ffffffff81e7e21c)
Location: drivers/mmc/core/host.h:30
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
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
In drivers/mmc/core/core.c (ffff800010b303d0)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffff800010b3c278)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
```
In drivers/mmc/core/block.c (ffff800010b43070)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_recovery
  - drivers/mmc/core/block.c:mmc_blk_fix_state
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
In drivers/mmc/core/core.c (c0c0b204)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (c0c1696c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
```
In drivers/mmc/core/block.c (c0c1ccf0)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_recovery
  - drivers/mmc/core/block.c:mmc_blk_fix_state
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
In drivers/mmc/core/core.c (c000000000c29c28)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (c000000000c39150)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
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
In drivers/mmc/core/core.c (ffffffe000708fb2)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffe0007137ae)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
```
In drivers/mmc/core/block.c (ffffffe000718d70)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_recovery
  - drivers/mmc/core/block.c:mmc_blk_fix_state
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
In drivers/mmc/core/core.c (ffffffff81879cab)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff8188566c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818cb14b)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818d6b0c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
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
In drivers/mmc/core/core.c (ffffffff818e7c6b)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_cqe_recovery
```
```
In drivers/mmc/core/sdio_io.c (ffffffff818f362c)
Location: drivers/mmc/core/host.h:24
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_io.c:sdio_retune_hold_now
```
</details>
</li>
</ul>

## Differences
