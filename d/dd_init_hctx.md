# Function: <code>dd_init_hctx</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dd_init_hctx(struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81601e80)
Location: block/mq-deadline.c:526
Inline: False
```
**Symbols:**

```
ffffffff81601e80-ffffffff81601ecc: dd_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dd_init_hctx(struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b4ce0)
Location: block/mq-deadline.c:574
Inline: False
```
**Symbols:**

```
ffffffff816b4ce0-ffffffff816b4d38: dd_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dd_init_hctx(struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817747b0)
Location: block/mq-deadline.c:632
Inline: False
```
**Symbols:**

```
ffffffff817747b0-ffffffff81774808: dd_init_hctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dd_init_hctx(struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:657
Inline: False
```
**Symbols:**

```
ffffffff817b2d30-ffffffff817b2d9c: dd_init_hctx (STB_LOCAL)
ffffffff820f6e54-ffffffff820f6e72: dd_init_hctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dd_init_hctx(struct blk_mq_hw_ctx *hctx, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (0)
Location: block/mq-deadline.c:657
Inline: False
```
**Symbols:**

```
ffffffff817f6b60-ffffffff817f6bcc: dd_init_hctx (STB_LOCAL)
ffffffff821d42b6-ffffffff821d42d4: dd_init_hctx.cold (STB_LOCAL)
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
