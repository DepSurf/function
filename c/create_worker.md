# Function: <code>create_worker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81099ce0)
Location: kernel/workqueue.c:1697
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:init_workqueues
```
**Symbols:**

```
ffffffff81099ce0-ffffffff81099e88: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d270)
Location: kernel/workqueue.c:1753
Inline: False
Direct callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff8109d270-ffffffff8109d413: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1de0)
Location: kernel/workqueue.c:1755
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a1de0-ffffffff810a1f83: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109f2f0)
Location: kernel/workqueue.c:1754
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff8109f2f0-ffffffff8109f493: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a5b20)
Location: kernel/workqueue.c:1755
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a5b20-ffffffff810a5cc3: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810abc90)
Location: kernel/workqueue.c:1790
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810abc90-ffffffff810abe34: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b5740)
Location: kernel/workqueue.c:1810
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810b5740-ffffffff810b58e7: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb630)
Location: kernel/workqueue.c:1906
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bb630-ffffffff810bb7d9: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c18a0)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c18a0-ffffffff810c1a49: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8770)
Location: kernel/workqueue.c:1906
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:maybe_create_worker
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c8770-ffffffff810c8955: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c38d0)
Location: kernel/workqueue.c:1912
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:maybe_create_worker
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c38d0-ffffffff810c3ab5: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5210)
Location: kernel/workqueue.c:1913
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c5210-ffffffff810c53b9: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d7e00)
Location: kernel/workqueue.c:1943
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810d7e00-ffffffff810d7fa7: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f0010)
Location: kernel/workqueue.c:1926
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810f0010-ffffffff810f01bd: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811119d0)
Location: kernel/workqueue.c:1926
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff811119d0-ffffffff81111b7d: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2128
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff8111e440-ffffffff8111e697: create_worker (STB_LOCAL)
ffffffff820d4a47-ffffffff820d4a83: create_worker.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2168
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff81128e60-ffffffff811290f4: create_worker (STB_LOCAL)
ffffffff821af9a1-ffffffff821af9f9: create_worker.cold (STB_LOCAL)
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
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011e240)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffff80001011e240-ffff80001011e434: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0371420)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
c0371420-c03715d4: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000168080)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
c000000000168080-c0000000001682f0: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7b08)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffe0000d7b08-ffffffe0000d7ca2: create_worker (STB_LOCAL)
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
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bbc10)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bbc10-ffffffff810bbdb9: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a9920)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810a9920-ffffffff810a9ac3: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bb170)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810bb170-ffffffff810bb319: create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct worker *create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1400)
Location: kernel/workqueue.c:1909
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_prepare_cpu
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:workqueue_init
  - kernel/workqueue.c:workqueue_init
```
**Symbols:**

```
ffffffff810c1400-ffffffff810c159d: create_worker (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
