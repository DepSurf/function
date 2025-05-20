# Function: <code>try_to_take_rt_mutex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cae70)
Location: kernel/locking/rtmutex.c:766
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff810cae70-ffffffff810caf5a: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cf960)
Location: kernel/locking/rtmutex.c:767
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810cf960-ffffffff810cfa4a: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6340)
Location: kernel/locking/rtmutex.c:831
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810d6340-ffffffff810d642d: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d52e0)
Location: kernel/locking/rtmutex.c:820
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810d52e0-ffffffff810d53fa: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dd190)
Location: kernel/locking/rtmutex.c:808
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810dd190-ffffffff810dd2da: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e5840)
Location: kernel/locking/rtmutex.c:808
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810e5840-ffffffff810e5991: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f0dd0)
Location: kernel/locking/rtmutex.c:808
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810f0dd0-ffffffff810f0f1c: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f9560)
Location: kernel/locking/rtmutex.c:809
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810f9560-ffffffff810f96b2: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105350)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81105350-ffffffff811054a2: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110110)
Location: kernel/locking/rtmutex.c:805
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81110110-ffffffff81110259: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110d2c0)
Location: kernel/locking/rtmutex.c:805
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff8110d2c0-ffffffff8110d409: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c35e80)
Location: kernel/locking/rtmutex.c:782
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81c35e80-ffffffff81c36085: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex_base *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54690)
Location: kernel/locking/rtmutex.c:962
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:__rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
```
**Symbols:**

```
ffffffff81d54690-ffffffff81d548f8: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex_base *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f261d0)
Location: kernel/locking/rtmutex.c:971
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
```
**Symbols:**

```
ffffffff81f261d0-ffffffff81f2645d: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex_base *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d1ca0)
Location: kernel/locking/rtmutex.c:1009
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
```
**Symbols:**

```
ffffffff820d1ca0-ffffffff820d1f2d: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex_base *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82156000)
Location: kernel/locking/rtmutex.c:1064
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
```
**Symbols:**

```
ffffffff82156000-ffffffff8215629b: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex_base *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82238e40)
Location: kernel/locking/rtmutex.c:1083
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex_api.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex_api.c:rt_mutex_trylock
```
**Symbols:**

```
ffffffff82238e40-ffffffff822390db: try_to_take_rt_mutex (STB_LOCAL)
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
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016b028)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffff80001016b028-ffff80001016b1d4: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b6c28)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
c03b6c28-c03b6dbc: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c2930)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
c0000000001c2930-c0000000001c2b40: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010b632)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffe00010b632-ffffffe00010b76e: try_to_take_rt_mutex (STB_LOCAL)
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
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fe660)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810fe660-ffffffff810fe7b2: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ee860)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810ee860-ffffffff810ee9b2: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fb820)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810fb820-ffffffff810fb972: try_to_take_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int try_to_take_rt_mutex(struct rt_mutex *lock, struct task_struct *task, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff811069f0)
Location: kernel/locking/rtmutex.c:807
Inline: True
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_trylock
  - kernel/locking/rtmutex.c:__rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_futex_trylock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:__rt_mutex_slowlock
```
**Symbols:**

```
ffffffff811069f0-ffffffff81106b40: try_to_take_rt_mutex (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt_mutex *lock</code> ➡️ <code>struct rt_mutex_base *lock</code>
</li>
</ul>
</details>
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
