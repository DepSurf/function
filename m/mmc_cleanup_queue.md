# Function: <code>mmc_cleanup_queue</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void mmc_cleanup_queue(struct mmc_queue *mq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/queue.c (ffff800010b44688)
Location: drivers/mmc/core/queue.c:498
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffff800010b44688-ffff800010b446e4: mmc_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_cleanup_queue(struct mmc_queue *mq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/queue.c (c0c1e1e8)
Location: drivers/mmc/core/queue.c:498
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
c0c1e1e8-c0c1e240: mmc_cleanup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_cleanup_queue(struct mmc_queue *mq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/queue.c (ffffffe000719f5e)
Location: drivers/mmc/core/queue.c:498
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_remove_req
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffffffe000719f5e-ffffffe000719fc0: mmc_cleanup_queue (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
