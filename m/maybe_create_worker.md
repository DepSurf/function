# Function: <code>maybe_create_worker</code>

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
In kernel/workqueue.c (ffffffff8109a5fb)
Location: kernel/workqueue.c:1869
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff8109dbe1)
Location: kernel/workqueue.c:1925
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810a2752)
Location: kernel/workqueue.c:1927
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff8109fbb4)
Location: kernel/workqueue.c:1926
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810a63d7)
Location: kernel/workqueue.c:1927
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810ad210)
Location: kernel/workqueue.c:1961
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810b5ff0)
Location: kernel/workqueue.c:1981
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810bbe41)
Location: kernel/workqueue.c:2077
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810c20e1)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void maybe_create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c8960)
Location: kernel/workqueue.c:2077
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c8960-ffffffff810c8a33: maybe_create_worker (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void maybe_create_worker(struct worker_pool *pool);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3ac0)
Location: kernel/workqueue.c:2083
Inline: False
Direct callers:
  - kernel/workqueue.c:worker_thread
```
**Symbols:**

```
ffffffff810c3ac0-ffffffff810c3b93: maybe_create_worker (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810c6675)
Location: kernel/workqueue.c:2084
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810d9334)
Location: kernel/workqueue.c:2113
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810f2f0e)
Location: kernel/workqueue.c:2096
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff8111452e)
Location: kernel/workqueue.c:2096
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff81122088)
Location: kernel/workqueue.c:2406
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff8112af5e)
Location: kernel/workqueue.c:2454
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffff80001012061c)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (c03744a4)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (c000000000168c3c)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffe0000d90a4)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810bc451)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810aacd5)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810bb9b1)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
In kernel/workqueue.c (ffffffff810c3d90)
Location: kernel/workqueue.c:2080
Inline: True
Inline callers:
  - kernel/workqueue.c:worker_thread
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
