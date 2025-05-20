# Function: <code>blk_mq_hctx_notify_online</code>

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
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154f790)
Location: block/blk-mq.c:2405
Inline: False
```
**Symbols:**

```
ffffffff8154f790-ffffffff8154f7c3: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156bb70)
Location: block/blk-mq.c:2506
Inline: False
```
**Symbols:**

```
ffffffff8156bb70-ffffffff8156bba3: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573370)
Location: block/blk-mq.c:2567
Inline: False
```
**Symbols:**

```
ffffffff81573370-ffffffff815733a3: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7990)
Location: block/blk-mq.c:2590
Inline: False
```
**Symbols:**

```
ffffffff815d7990-ffffffff815d79c3: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816829c0)
Location: block/blk-mq.c:3345
Inline: False
```
**Symbols:**

```
ffffffff816829c0-ffffffff816829f7: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817400c0)
Location: block/blk-mq.c:3509
Inline: False
```
**Symbols:**

```
ffffffff817400c0-ffffffff817400f7: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177c5b0)
Location: block/blk-mq.c:3521
Inline: False
```
**Symbols:**

```
ffffffff8177c5b0-ffffffff8177c5e7: blk_mq_hctx_notify_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_hctx_notify_online(unsigned int cpu, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817be940)
Location: block/blk-mq.c:3537
Inline: False
```
**Symbols:**

```
ffffffff817be940-ffffffff817be977: blk_mq_hctx_notify_online (STB_LOCAL)
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
