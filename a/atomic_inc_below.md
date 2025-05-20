# Function: <code>atomic_inc_below</code>

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
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ad882)
Location: kernel/ucount.c:176
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-wbt.c (ffffffff8144ab91)
Location: block/blk-wbt.c:65
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810aa462)
Location: kernel/ucount.c:181
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-wbt.c (ffffffff81458e13)
Location: block/blk-wbt.c:65
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b0cc2)
Location: kernel/ucount.c:181
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-wbt.c (ffffffff81484b6e)
Location: block/blk-wbt.c:65
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b7ae9)
Location: kernel/ucount.c:182
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-wbt.c (ffffffff814b993f)
Location: block/blk-wbt.c:85
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_wait
  - block/blk-wbt.c:wbt_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c0be9)
Location: kernel/ucount.c:182
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff814bd795)
Location: block/blk-rq-qos.c:7
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c6cee)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff814ebe45)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810cfdbe)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff81505205)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9db4)
Location: kernel/ucount.c:178
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff81565ad5)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d4f65)
Location: kernel/ucount.c:178
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff81580a55)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d6c44)
Location: kernel/ucount.c:215
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff815885c5)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
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
In block/blk-rq-qos.c (ffffffff815ee265)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
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
In block/blk-rq-qos.c (ffffffff8169ea55)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
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
In block/blk-rq-qos.c (ffffffff8175d255)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
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
In block/blk-rq-qos.c (ffffffff8179bfb5)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
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
In block/blk-rq-qos.c (ffffffff817dfa15)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffff8000101302b8)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffff800010607204)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c037fb30)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (c07b2484)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (c0000000001798d4)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (c0000000007a3b9c)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffe0000e3824)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffe000441f30)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810ca13e)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff814fd7e5)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810b8958)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff814edcf5)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810c966e)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff814f9875)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d1bbc)
Location: kernel/ucount.c:175
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In block/blk-rq-qos.c (ffffffff815128d5)
Location: block/blk-rq-qos.c:9
Inline: True
Inline callers:
  - block/blk-rq-qos.c:rq_wait_inc_below
```
</details>
</li>
</ul>

## Differences
