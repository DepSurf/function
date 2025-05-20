# Function: <code>worker_pool_assign_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b909)
Location: kernel/workqueue.c:540
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:init_workqueues
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81fa52c8)
Location: kernel/workqueue.c:531
Inline: True
Inline callers:
  - kernel/workqueue.c:init_workqueues
  - kernel/workqueue.c:alloc_unbound_pwq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3f3d)
Location: kernel/workqueue.c:533
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a106b)
Location: kernel/workqueue.c:533
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a78d7)
Location: kernel/workqueue.c:535
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ae405)
Location: kernel/workqueue.c:533
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b7565)
Location: kernel/workqueue.c:533
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bc90c)
Location: kernel/workqueue.c:536
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c365c)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int worker_pool_assign_id(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810caf00)
Location: kernel/workqueue.c:532
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff810ccc9c-ffffffff810cccd1: worker_pool_assign_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int worker_pool_assign_id(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6030)
Location: kernel/workqueue.c:532
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff81bdbaf1-ffffffff81bdbb26: worker_pool_assign_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int worker_pool_assign_id(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c796e)
Location: kernel/workqueue.c:533
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff81bcdba9-ffffffff81bcdbde: worker_pool_assign_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int worker_pool_assign_id(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da6da)
Location: kernel/workqueue.c:550
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff81ca4c3c-ffffffff81ca4c71: worker_pool_assign_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int worker_pool_assign_id(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f3e35)
Location: kernel/workqueue.c:552
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
```
**Symbols:**

```
ffffffff81e544f2-ffffffff81e54536: worker_pool_assign_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81116082)
Location: kernel/workqueue.c:552
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81122e22)
Location: kernel/workqueue.c:594
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112ce86)
Location: kernel/workqueue.c:620
Inline: True
Inline callers:
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff8000101212ec)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375150)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016a8a8)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000da2bc)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bd9cc)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ac1fc)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bcf2c)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c52ac)
Location: kernel/workqueue.c:537
Inline: True
Inline callers:
  - kernel/workqueue.c:alloc_unbound_pwq
  - kernel/workqueue.c:workqueue_init_early
```
</details>
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
</ul>
