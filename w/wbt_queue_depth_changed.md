# Function: <code>wbt_queue_depth_changed</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8151a62d)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff815198e0-ffffffff8151990b: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157ad7d)
Location: block/blk-wbt.c:677
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8157a2f0-ffffffff8157a31b: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81597120)
Location: block/blk-wbt.c:677
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81597120-ffffffff815971db: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159dee0)
Location: block/blk-wbt.c:682
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8159dee0-ffffffff8159df9b: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816065c0)
Location: block/blk-wbt.c:684
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff816065c0-ffffffff81606697: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba330)
Location: block/blk-wbt.c:684
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff816ba330-ffffffff816ba40f: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a8b0)
Location: block/blk-wbt.c:702
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8177a8b0-ffffffff8177a98f: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba8f0)
Location: block/blk-wbt.c:764
Inline: False
```
**Symbols:**

```
ffffffff817ba8f0-ffffffff817ba929: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ff060)
Location: block/blk-wbt.c:756
Inline: False
```
**Symbols:**

```
ffffffff817ff060-ffffffff817ff099: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff8000106224e0)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffff800010620e50-ffff800010620e90: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07ca0a8)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
c07c8f0c-c07c8f40: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c25bc)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
c0000000007c1310-c0000000007c1344: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe0004544d6)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffe000453936-ffffffe000453970: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81512c0d)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81511ec0-ffffffff81511eeb: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502f2d)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff815021e0-ffffffff8150220b: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150ec9d)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8150df50-ffffffff8150df7b: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wbt_queue_depth_changed(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8152846d)
Location: block/blk-wbt.c:685
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff81527570-ffffffff8152759b: wbt_queue_depth_changed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
