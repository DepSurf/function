# Function: <code>init_worker_pool</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b590)
Location: kernel/workqueue.c:3075
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:init_workqueues
```
**Symbols:**

```
ffffffff8109b590-ffffffff8109b6d6: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109eb90)
Location: kernel/workqueue.c:3175
Inline: False
Direct callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:alloc_unbound_pwq
```
**Symbols:**

```
ffffffff8109eb90-ffffffff8109ece1: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3a60)
Location: kernel/workqueue.c:3201
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810a3a60-ffffffff810a3bb1: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0be0)
Location: kernel/workqueue.c:3200
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810a0be0-ffffffff810a0d33: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7460)
Location: kernel/workqueue.c:3214
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810a7460-ffffffff810a7579: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810adff0)
Location: kernel/workqueue.c:3288
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810adff0-ffffffff810ae0f6: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b7120)
Location: kernel/workqueue.c:3311
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810b7120-ffffffff810b7226: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ba6b0)
Location: kernel/workqueue.c:3410
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810ba6b0-ffffffff810ba7b1: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3200)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810c3200-ffffffff810c3301: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cac80)
Location: kernel/workqueue.c:3416
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810cac80-ffffffff810cad98: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c5db0)
Location: kernel/workqueue.c:3422
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810c5db0-ffffffff810c5ec8: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c76f0)
Location: kernel/workqueue.c:3423
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810c76f0-ffffffff810c7808: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da450)
Location: kernel/workqueue.c:3462
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810da450-ffffffff810da568: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f3b80)
Location: kernel/workqueue.c:3445
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810f3b80-ffffffff810f3ca7: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81115dc0)
Location: kernel/workqueue.c:3452
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff81115dc0-ffffffff81115ee7: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81122b20)
Location: kernel/workqueue.c:3768
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff81122b20-ffffffff81122c90: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112caf0)
Location: kernel/workqueue.c:3858
Inline: False
Direct callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff8112caf0-ffffffff8112cc6d: init_worker_pool (STB_LOCAL)
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
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010120f80)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffff800010120f80-ffff80001012106c: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0374ec8)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
c0374ec8-c0374fc8: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016a4a0)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
c00000000016a4a0-c00000000016a5d8: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d9ef2)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffe0000d9ef2-ffffffe0000d9fca: init_worker_pool (STB_LOCAL)
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
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd570)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810bd570-ffffffff810bd671: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810abda0)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810abda0-ffffffff810abea1: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bcad0)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810bcad0-ffffffff810bcbd1: init_worker_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_worker_pool(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4e50)
Location: kernel/workqueue.c:3419
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810c4e50-ffffffff810c4f51: init_worker_pool (STB_LOCAL)
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
