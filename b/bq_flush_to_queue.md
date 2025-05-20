# Function: <code>bq_flush_to_queue</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int bq_flush_to_queue(struct bpf_cpu_map_entry *rcpu, struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811af740)
Location: kernel/bpf/cpumap.c:597
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811af740-ffffffff811af87d: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bq_flush_to_queue(struct bpf_cpu_map_entry *rcpu, struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ca240)
Location: kernel/bpf/cpumap.c:560
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811ca240-ffffffff811ca398: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bq_flush_to_queue(struct bpf_cpu_map_entry *rcpu, struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ddb60)
Location: kernel/bpf/cpumap.c:563
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811ddb60-ffffffff811ddcb8: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f3210)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811f3210-ffffffff811f3386: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811fffb0)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811fffb0-ffffffff81200126: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81227bb0)
Location: kernel/bpf/cpumap.c:556
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81227bb0-ffffffff81227d1c: bq_flush_to_queue.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8122e5c0)
Location: kernel/bpf/cpumap.c:659
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff8122e5c0-ffffffff8122e70d: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812334a0)
Location: kernel/bpf/cpumap.c:622
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff812334a0-ffffffff812335ed: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126e340)
Location: kernel/bpf/cpumap.c:689
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff8126e340-ffffffff8126e49f: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bd260)
Location: kernel/bpf/cpumap.c:691
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff812bd260-ffffffff812bd3d7: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff813206d0)
Location: kernel/bpf/cpumap.c:690
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff813206d0-ffffffff81320847: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81350580)
Location: kernel/bpf/cpumap.c:711
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81350580-ffffffff813506f7: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bq_flush_to_queue(struct xdp_bulk_queue *bq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81377a50)
Location: kernel/bpf/cpumap.c:665
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81377a50-ffffffff81377bc7: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffff800010288450)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffff800010288450-ffff80001028863c: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c04b789c)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
c04b789c-c04b7a3c: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c000000000332b50)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
c000000000332b50-c000000000332dbc: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffe0001bc3f0)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffe0001bc3f0-ffffffe0001bc56e: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f85d0)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811f85d0-ffffffff811f8746: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811eb320)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811eb320-ffffffff811eb496: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f63a0)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff811f63a0-ffffffff811f6516: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bq_flush_to_queue(struct xdp_bulk_queue *bq, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81204910)
Location: kernel/bpf/cpumap.c:602
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:__cpu_map_flush
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - kernel/bpf/cpumap.c:__cpu_map_entry_free
```
**Symbols:**

```
ffffffff81204910-ffffffff81204a9f: bq_flush_to_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool in_napi_ctx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_cpu_map_entry *rcpu</code>
</li>
<li>
<b>Param reordered. </b>
<code>rcpu, bq, in_napi_ctx</code> ➡️ <code>bq, in_napi_ctx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
