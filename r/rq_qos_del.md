# Function: <code>rq_qos_del</code>

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
In block/blk-iocost.c (ffffffff8151206c)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff81573026)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff8158f999)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff8159694c)
Location: block/blk-rq-qos.h:123
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff815fdf63)
Location: block/blk-rq-qos.h:111
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff816ae6ba)
Location: block/blk-rq-qos.h:123
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff8176d3ba)
Location: block/blk-rq-qos.h:122
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rq_qos_del(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff8179c8e0)
Location: block/blk-rq-qos.c:336
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff8179c8e0-ffffffff8179c96b: rq_qos_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rq_qos_del(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff817e0350)
Location: block/blk-rq-qos.c:336
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff817e0350-ffffffff817e03e1: rq_qos_del (STB_GLOBAL)
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
In block/blk-iocost.c (0)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (c07bff50)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (c0000000007b4f10)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffe00044c8ba)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff8150a64c)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff814faad6)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff815066dc)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
In block/blk-iocost.c (ffffffff8151f9c3)
Location: block/blk-rq-qos.h:109
Inline: True
Inline callers:
  - block/blk-iocost.c:blk_iocost_init
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
