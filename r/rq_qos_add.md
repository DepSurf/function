# Function: <code>rq_qos_add</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cddda)
Location: block/blk-rq-qos.h:94
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-wbt.c (ffffffff814fc691)
Location: block/blk-rq-qos.h:95
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff8151202a)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8151a5e1)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff81572fe6)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8157ad31)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff8158f959)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81597e07)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff815968da)
Location: block/blk-rq-qos.h:101
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8159ebe0)
Location: block/blk-rq-qos.h:101
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-ioprio.c (ffffffff815f96b9)
Location: block/blk-rq-qos.h:89
Inline: True
Inline callers:
  - block/blk-ioprio.c:blk_ioprio_init
```
```
In block/blk-iocost.c (ffffffff815fdef0)
Location: block/blk-rq-qos.h:89
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81607350)
Location: block/blk-rq-qos.h:89
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-ioprio.c (ffffffff816ab6dc)
Location: block/blk-rq-qos.h:89
Inline: True
Inline callers:
  - block/blk-ioprio.c:blk_ioprio_init
```
```
In block/blk-iocost.c (ffffffff816ae5e9)
Location: block/blk-rq-qos.h:89
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff816baed9)
Location: block/blk-rq-qos.h:89
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff8176d2e6)
Location: block/blk-rq-qos.h:88
Inline: True
```
```
In block/blk-wbt.c (ffffffff8177b5b6)
Location: block/blk-rq-qos.h:88
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rq_qos_add(struct rq_qos *rqos, struct gendisk *disk, enum rq_qos_id id, const struct rq_qos_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8179c820)
Location: block/blk-rq-qos.c:300
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8179c820-ffffffff8179c8c1: rq_qos_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rq_qos_add(struct rq_qos *rqos, struct gendisk *disk, enum rq_qos_id id, const struct rq_qos_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff817e0290)
Location: block/blk-rq-qos.c:300
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff817e0290-ffffffff817e0337: rq_qos_add (STB_GLOBAL)
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
In block/blk-iocost.c (ffff800010615720)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffff800010622494)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (c07bff08)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (c07ca05c)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (c0000000007b4ea8)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (c0000000007c2574)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffe00044c87a)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffe00045449c)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff8150a60a)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81512bc1)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff814faa94)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81502ee1)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff8150669a)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff8150ec51)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
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
In block/blk-iocost.c (ffffffff8151f981)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/blk-wbt.c (ffffffff81528421)
Location: block/blk-rq-qos.h:100
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
