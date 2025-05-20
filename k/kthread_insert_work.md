# Function: <code>kthread_insert_work</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8f20)
Location: kernel/kthread.c:764
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810a8f20-ffffffff810a8f77: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5cb0)
Location: kernel/kthread.c:770
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810a5cb0-ffffffff810a5d07: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac280)
Location: kernel/kthread.c:777
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810ac280-ffffffff810ac2d7: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b2bd0)
Location: kernel/kthread.c:795
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810b2bd0-ffffffff810b2c27: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bbe50)
Location: kernel/kthread.c:797
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810bbe50-ffffffff810bbea7: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1fa0)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810c1fa0-ffffffff810c1ff7: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8500)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810c8500-ffffffff810c8557: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0290)
Location: kernel/kthread.c:842
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff810d0290-ffffffff810d02e3: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cac80)
Location: kernel/kthread.c:893
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff810cac80-ffffffff810cad0c: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc590)
Location: kernel/kthread.c:920
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff810cc590-ffffffff810cc61c: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810dfa70)
Location: kernel/kthread.c:920
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff810dfa70-ffffffff810dfb13: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa2c0)
Location: kernel/kthread.c:980
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff810fa2c0-ffffffff810fa394: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d070)
Location: kernel/kthread.c:981
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff8111d070-ffffffff8111d144: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a190)
Location: kernel/kthread.c:982
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff8112a190-ffffffff8112a264: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134820)
Location: kernel/kthread.c:999
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_worker
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
```
**Symbols:**

```
ffffffff81134820-ffffffff811348f4: kthread_insert_work (STB_LOCAL)
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
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127310)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffff800010127310-ffff800010127388: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a148)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
c037a148-c037a1a4: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171ce0)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
c000000000171ce0-c000000000171d90: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dee66)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffe0000dee66-ffffffe0000deed4: kthread_insert_work (STB_LOCAL)
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
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2880)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810c2880-ffffffff810c28d7: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b10d0)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810b10d0-ffffffff810b1127: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1dd0)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810c1dd0-ffffffff810c1e27: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kthread_insert_work(struct kthread_worker *worker, struct kthread_work *work, struct list_head *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca3b0)
Location: kernel/kthread.c:806
Inline: True
Direct callers:
  - kernel/kthread.c:kthread_flush_work
  - kernel/kthread.c:__kthread_queue_delayed_work
  - kernel/kthread.c:kthread_delayed_work_timer_fn
  - kernel/kthread.c:kthread_queue_work
```
**Symbols:**

```
ffffffff810ca3b0-ffffffff810ca407: kthread_insert_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
