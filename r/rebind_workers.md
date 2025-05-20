# Function: <code>rebind_workers</code>

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
In kernel/workqueue.c (ffffffff8109bdd4)
Location: kernel/workqueue.c:4413
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_cpu_up_callback
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
In kernel/workqueue.c (ffffffff810a027c)
Location: kernel/workqueue.c:4513
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810a535c)
Location: kernel/workqueue.c:4543
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810a24c4)
Location: kernel/workqueue.c:4563
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810a8d55)
Location: kernel/workqueue.c:4601
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810af4f4)
Location: kernel/workqueue.c:4720
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810b8664)
Location: kernel/workqueue.c:4743
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810be17b)
Location: kernel/workqueue.c:4888
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810c471b)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rebind_workers(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8570)
Location: kernel/workqueue.c:4945
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
```
**Symbols:**

```
ffffffff810c8570-ffffffff810c863e: rebind_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rebind_workers(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c36c0)
Location: kernel/workqueue.c:4964
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
```
**Symbols:**

```
ffffffff810c36c0-ffffffff810c379b: rebind_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8cd3)
Location: kernel/workqueue.c:4971
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810db903)
Location: kernel/workqueue.c:5024
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f51f3)
Location: kernel/workqueue.c:5020
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff81117703)
Location: kernel/workqueue.c:5029
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff81124743)
Location: kernel/workqueue.c:5422
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff8112ee43)
Location: kernel/workqueue.c:5445
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffff800010122a90)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (c0376400)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (c00000000016c710)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffe0000db362)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810bea8b)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810ad2bb)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810bdfeb)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
In kernel/workqueue.c (ffffffff810c635b)
Location: kernel/workqueue.c:4922
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_online_cpu
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
</ul>
