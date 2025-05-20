# Function: <code>ww_mutex_init</code>

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
In drivers/dma-buf/dma-buf.c (ffffffff815a30d2)
Location: include/linux/ww_mutex.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/dma-buf/dma-buf.c (ffffffff815fa145)
Location: include/linux/ww_mutex.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/dma-buf/dma-buf.c (ffffffff81628412)
Location: include/linux/ww_mutex.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/dma-buf/dma-buf.c (ffffffff8163dd2c)
Location: include/linux/ww_mutex.h:85
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/dma-buf/dma-buf.c (ffffffff816a6aac)
Location: include/linux/ww_mutex.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/dma-buf/dma-buf.c (ffffffff816e2d66)
Location: include/linux/ww_mutex.h:86
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/regulator/core.c (ffffffff81627af1)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81706208)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/regulator/core.c (ffffffff8165bf18)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-buf.c (ffffffff817412ef)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_export
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
In drivers/regulator/core.c (ffffffff8167dcff)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81767a45)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff8172f42f)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81828425)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff8174c061)
Location: include/linux/ww_mutex.h:87
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81838e75)
Location: include/linux/ww_mutex.h:87
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff8172f7f1)
Location: include/linux/ww_mutex.h:74
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8181c135)
Location: include/linux/ww_mutex.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff817af5ed)
Location: include/linux/ww_mutex.h:100
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff818a65c5)
Location: include/linux/ww_mutex.h:100
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff818ea9bc)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f05e5)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff81a414e3)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6e125)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff81a8b5ba)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc1935)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff81addd4b)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c160c5)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca8645)
Location: include/linux/ww_mutex.h:98
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_lock_init
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
In drivers/regulator/core.c (ffff800010847a5c)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffff800010968cb0)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (c0951308)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (c0a3ede8)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (c0000000008e3fe8)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (c000000000a20a10)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffe000527dfe)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4860)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff8164375f)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8171c135)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff81623bdf)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff816f5595)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff81671b3f)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff8175af05)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
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
In drivers/regulator/core.c (ffffffff8168c19f)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
```
```
In drivers/dma-buf/dma-resv.c (ffffffff817764e5)
Location: include/linux/ww_mutex.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_init
```
</details>
</li>
</ul>

## Differences
