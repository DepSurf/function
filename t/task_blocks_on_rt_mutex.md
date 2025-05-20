# Function: <code>task_blocks_on_rt_mutex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cb390)
Location: kernel/locking/rtmutex.c:888
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff810cb390-ffffffff810cb543: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cfe20)
Location: kernel/locking/rtmutex.c:887
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810cfe20-ffffffff810cffbe: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6810)
Location: kernel/locking/rtmutex.c:951
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810d6810-ffffffff810d69ae: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5870)
Location: kernel/locking/rtmutex.c:941
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810d5870-ffffffff810d5a33: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dd7d0)
Location: kernel/locking/rtmutex.c:929
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810dd7d0-ffffffff810dd9b7: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e5e40)
Location: kernel/locking/rtmutex.c:929
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810e5e40-ffffffff810e6033: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f13c0)
Location: kernel/locking/rtmutex.c:929
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810f13c0-ffffffff810f15b1: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f9c00)
Location: kernel/locking/rtmutex.c:930
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810f9c00-ffffffff810f9e27: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff811059f0)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff811059f0-ffffffff81105c17: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff811108d0)
Location: kernel/locking/rtmutex.c:926
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff811108d0-ffffffff81110b3d: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110da80)
Location: kernel/locking/rtmutex.c:926
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff8110da80-ffffffff8110dced: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c36a50)
Location: kernel/locking/rtmutex.c:900
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff81c36a50-ffffffff81c36de8: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55630)
Location: kernel/locking/rtmutex.c:1078
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:__rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff81d55630-ffffffff81d559d6: task_blocks_on_rt_mutex.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f272d0)
Location: kernel/locking/rtmutex.c:1087
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff81f272d0-ffffffff81f27696: task_blocks_on_rt_mutex.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d2da0)
Location: kernel/locking/rtmutex.c:1125
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff820d2da0-ffffffff820d3166: task_blocks_on_rt_mutex.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff821570f0)
Location: kernel/locking/rtmutex.c:1180
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff821570f0-ffffffff821574bb: task_blocks_on_rt_mutex.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82239f30)
Location: kernel/locking/rtmutex.c:1199
Inline: True
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff82239f30-ffffffff8223a2fb: task_blocks_on_rt_mutex.constprop.0 (STB_LOCAL)
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
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016b9c0)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffff80001016b9c0-ffff80001016bc80: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7474)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
c03b7474-c03b769c: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3460)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
c0000000001c3460-c0000000001c3784: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010bdbc)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffe00010bdbc-ffffffe00010bfda: task_blocks_on_rt_mutex (STB_LOCAL)
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
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fed00)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810fed00-ffffffff810fef27: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810eeef0)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810eeef0-ffffffff810ef111: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fbec0)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810fbec0-ffffffff810fc0e7: task_blocks_on_rt_mutex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int task_blocks_on_rt_mutex(struct rt_mutex *lock, struct rt_mutex_waiter *waiter, struct task_struct *task, enum rtmutex_chainwalk chwalk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff811070e0)
Location: kernel/locking/rtmutex.c:928
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff811070e0-ffffffff81107323: task_blocks_on_rt_mutex (STB_LOCAL)
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
