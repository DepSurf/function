# Function: <code>blk_mq_hctx_notify_offline</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154f850)
Location: block/blk-mq.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8154f850-ffffffff8154f9ba: blk_mq_hctx_notify_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156bc30)
Location: block/blk-mq.c:2473
Inline: False
```
**Symbols:**

```
ffffffff8156bc30-ffffffff8156bd9b: blk_mq_hctx_notify_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573720)
Location: block/blk-mq.c:2534
Inline: False
```
**Symbols:**

```
ffffffff81573720-ffffffff8157388d: blk_mq_hctx_notify_offline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2557
Inline: False
```
**Symbols:**

```
ffffffff815d7d10-ffffffff815d7e90: blk_mq_hctx_notify_offline (STB_LOCAL)
ffffffff81cd834e-ffffffff81cd8363: blk_mq_hctx_notify_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3312
Inline: False
```
**Symbols:**

```
ffffffff81684440-ffffffff816845c1: blk_mq_hctx_notify_offline (STB_LOCAL)
ffffffff81e8b971-ffffffff81e8b986: blk_mq_hctx_notify_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3476
Inline: False
```
**Symbols:**

```
ffffffff81742260-ffffffff817423ec: blk_mq_hctx_notify_offline (STB_LOCAL)
ffffffff8207602d-ffffffff82076042: blk_mq_hctx_notify_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3488
Inline: False
```
**Symbols:**

```
ffffffff8177f2b0-ffffffff8177f43c: blk_mq_hctx_notify_offline (STB_LOCAL)
ffffffff820f5ea6-ffffffff820f5ebb: blk_mq_hctx_notify_offline.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blk_mq_hctx_notify_offline(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3504
Inline: False
```
**Symbols:**

```
ffffffff817c1da0-ffffffff817c1f2c: blk_mq_hctx_notify_offline (STB_LOCAL)
ffffffff821d33f3-ffffffff821d3408: blk_mq_hctx_notify_offline.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
