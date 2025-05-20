# Function: <code>init_pwq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81097a70)
Location: kernel/workqueue.c:3354
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__alloc_workqueue_key
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff81097a70-ffffffff81097a7b: init_pwq.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0f99)
Location: kernel/workqueue.c:3455
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8109b150-ffffffff8109b15b: init_pwq.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a6063)
Location: kernel/workqueue.c:3483
Inline: True
Inline callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8109ff30-ffffffff8109ff3b: init_pwq.part.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109dbe0)
Location: kernel/workqueue.c:3481
Inline: True
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8109dbe0-ffffffff8109dc9d: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4300)
Location: kernel/workqueue.c:3492
Inline: True
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810a4300-ffffffff810a43bc: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810aa8d0)
Location: kernel/workqueue.c:3565
Inline: True
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810aa8d0-ffffffff810aa98c: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b39a0)
Location: kernel/workqueue.c:3588
Inline: True
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810b39a0-ffffffff810b3a5c: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9680)
Location: kernel/workqueue.c:3729
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810b9680-ffffffff810b973d: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bfb20)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810bfb20-ffffffff810bfbdd: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6320)
Location: kernel/workqueue.c:3747
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810c6320-ffffffff810c63dd: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1380)
Location: kernel/workqueue.c:3760
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810c1380-ffffffff810c143d: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2d60)
Location: kernel/workqueue.c:3767
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810c2d60-ffffffff810c2e1d: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d58a0)
Location: kernel/workqueue.c:3806
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810d58a0-ffffffff810d5960: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810eec20)
Location: kernel/workqueue.c:3789
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810eec20-ffffffff810eecf1: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81110290)
Location: kernel/workqueue.c:3796
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff81110290-ffffffff81110361: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111c530)
Location: kernel/workqueue.c:4124
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8111c530-ffffffff8111c601: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81126280)
Location: kernel/workqueue.c:4190
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff81126280-ffffffff8112631c: init_pwq (STB_LOCAL)
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
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011c630)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffff80001011c630-ffff80001011c6c8: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0371324)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
c0371324-c03713c0: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000163ca0)
Location: kernel/workqueue.c:3738
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
c000000000163ca0-c000000000163d70: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dbeb8)
Location: kernel/workqueue.c:3738
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffe0000d6aaa-ffffffe0000d6abe: init_pwq.part.0 (STB_LOCAL)
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
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9e90)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810b9e90-ffffffff810b9f4d: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a87d0)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810a87d0-ffffffff810a888d: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b93f0)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810b93f0-ffffffff810b94ad: init_pwq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void init_pwq(struct pool_workqueue *pwq, struct workqueue_struct *wq, struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c1f10)
Location: kernel/workqueue.c:3738
Inline: True
Direct callers:
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff810c1f10-ffffffff810c1fcd: init_pwq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
