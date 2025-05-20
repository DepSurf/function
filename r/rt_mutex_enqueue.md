# Function: <code>rt_mutex_enqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cace0)
Location: kernel/locking/rtmutex.c:180
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
```
**Symbols:**

```
ffffffff810cace0-ffffffff810cad65: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cf7b0)
Location: kernel/locking/rtmutex.c:182
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810cf7b0-ffffffff810cf839: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6190)
Location: kernel/locking/rtmutex.c:246
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810d6190-ffffffff810d6219: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d50e0)
Location: kernel/locking/rtmutex.c:272
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810d50e0-ffffffff810d515b: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dcf90)
Location: kernel/locking/rtmutex.c:272
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810dcf90-ffffffff810dd001: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e5620)
Location: kernel/locking/rtmutex.c:272
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810e5620-ffffffff810e5691: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f0bb0)
Location: kernel/locking/rtmutex.c:272
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810f0bb0-ffffffff810f0c21: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f9290)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810f9290-ffffffff810f933d: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105080)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff81105080-ffffffff8110512d: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110fe70)
Location: kernel/locking/rtmutex.c:271
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff8110fe70-ffffffff8110ff1d: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110d020)
Location: kernel/locking/rtmutex.c:271
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff8110d020-ffffffff8110d0cd: rt_mutex_enqueue (STB_LOCAL)
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
In kernel/locking/rtmutex.c (ffffffff81c36ad0)
Location: kernel/locking/rtmutex.c:277
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
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
In kernel/locking/rtmutex_api.c (ffffffff81d54c90)
Location: kernel/locking/rtmutex.c:396
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/locking/rtmutex_api.c (ffffffff81f2683c)
Location: kernel/locking/rtmutex.c:398
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/locking/rtmutex_api.c (ffffffff820d22ec)
Location: kernel/locking/rtmutex.c:435
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/locking/rtmutex_api.c (ffffffff821566b0)
Location: kernel/locking/rtmutex.c:457
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
In kernel/locking/rtmutex_api.c (ffffffff822394f0)
Location: kernel/locking/rtmutex.c:476
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
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
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016acd8)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffff80001016acd8-ffff80001016ada8: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b6a2c)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
c03b6a2c-c03b6b08: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c2560)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
c0000000001c2560-c0000000001c266c: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010b386)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffe00010b386-ffffffe00010b422: rt_mutex_enqueue (STB_LOCAL)
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
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fe390)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810fe390-ffffffff810fe43d: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ee590)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810ee590-ffffffff810ee63d: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fb550)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff810fb550-ffffffff810fb5fd: rt_mutex_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_mutex_enqueue(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81106720)
Location: kernel/locking/rtmutex.c:273
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:task_blocks_on_rt_mutex
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
**Symbols:**

```
ffffffff81106720-ffffffff811067cd: rt_mutex_enqueue (STB_LOCAL)
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
