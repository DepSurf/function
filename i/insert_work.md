# Function: <code>insert_work</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81097fe0)
Location: kernel/workqueue.c:1270
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:flush_work
```
**Symbols:**

```
ffffffff81097fe0-ffffffff8109809c: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b520)
Location: kernel/workqueue.c:1291
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff8109b520-ffffffff8109b5dd: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0450)
Location: kernel/workqueue.c:1293
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810a0450-ffffffff810a050d: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109cac0)
Location: kernel/workqueue.c:1293
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff8109cac0-ffffffff8109cb39: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a3de0)
Location: kernel/workqueue.c:1295
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810a3de0-ffffffff810a3e53: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab130)
Location: kernel/workqueue.c:1293
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810ab130-ffffffff810ab1a3: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b4080)
Location: kernel/workqueue.c:1313
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b4080-ffffffff810b40f3: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9600)
Location: kernel/workqueue.c:1324
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b9600-ffffffff810b9673: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810befc0)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810befc0-ffffffff810bf03b: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7640)
Location: kernel/workqueue.c:1322
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c7640-ffffffff810c76bb: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2620)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c2620-ffffffff810c269b: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c4200)
Location: kernel/workqueue.c:1326
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c4200-ffffffff810c427f: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810d6d00)
Location: kernel/workqueue.c:1356
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810d6d00-ffffffff810d6d7f: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f0a40)
Location: kernel/workqueue.c:1352
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810f0a40-ffffffff810f0ad8: insert_work (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff811138d8)
Location: kernel/workqueue.c:1352
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff8111ffbb)
Location: kernel/workqueue.c:1550
Inline: True
Inline callers:
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff81129fa5)
Location: kernel/workqueue.c:1647
Inline: True
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
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011bb20)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffff80001011bb20-ffff80001011bbdc: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0371db0)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
c0371db0-c0371e78: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000163ab0)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
c000000000163ab0-c000000000163b88: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d5fa2)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffe0000d5fa2-ffffffe0000d6040: insert_work (STB_LOCAL)
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
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9330)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b9330-ffffffff810b93ab: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a7c70)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810a7c70-ffffffff810a7ceb: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8890)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810b8890-ffffffff810b890b: insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void insert_work(struct pool_workqueue *pwq, struct work_struct *work, struct list_head *head, unsigned int extra_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c0d20)
Location: kernel/workqueue.c:1325
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__queue_work
```
**Symbols:**

```
ffffffff810c0d20-ffffffff810c0d9b: insert_work (STB_LOCAL)
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
