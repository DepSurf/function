# Function: <code>queue_work_node</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb380)
Location: kernel/workqueue.c:1580
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810bb380-ffffffff810bb45c: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c15f0)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810c15f0-ffffffff810c16cc: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ca2f0)
Location: kernel/workqueue.c:1580
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810ca2f0-ffffffff810ca3cc: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5420)
Location: kernel/workqueue.c:1586
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810c5420-ffffffff810c54fc: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6d10)
Location: kernel/workqueue.c:1587
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810c6d10-ffffffff810c6e00: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1617
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff81ca5229-ffffffff81ca523e: queue_work_node.cold (STB_LOCAL)
ffffffff810d99c0-ffffffff810d9b2c: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1607
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff81e54a19-ffffffff81e54a2e: queue_work_node.cold (STB_LOCAL)
ffffffff810f1a00-ffffffff810f1b61: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1607
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff82056612-ffffffff82056627: queue_work_node.cold (STB_LOCAL)
ffffffff81115110-ffffffff81115277: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:1809
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff820d4b7e-ffffffff820d4b93: queue_work_node.cold (STB_LOCAL)
ffffffff811210e0-ffffffff81121247: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112b890)
Location: kernel/workqueue.c:1895
Inline: False
Direct callers:
  - kernel/async.c:__async_schedule_node_domain
```
**Symbols:**

```
ffffffff8112b890-ffffffff8112b9df: queue_work_node (STB_GLOBAL)
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
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011f9b0)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffff80001011f9b0-ffff80001011fb08: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c037294c)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
c037294c-c03729e4: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0000000001657c0)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
c0000000001657c0-c000000000165958: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d88b2)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffe0000d88b2-ffffffe0000d8910: queue_work_node (STB_GLOBAL)
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
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb960)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810bb960-ffffffff810bba3c: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa400)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810aa400-ffffffff810aa4c1: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810baec0)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810baec0-ffffffff810baf9c: queue_work_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool queue_work_node(int node, struct workqueue_struct *wq, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2770)
Location: kernel/workqueue.c:1583
Inline: False
Direct callers:
  - kernel/async.c:async_schedule_node_domain
```
**Symbols:**

```
ffffffff810c2770-ffffffff810c284c: queue_work_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
