# Function: <code>remove_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cb550)
Location: kernel/locking/rtmutex.c:1015
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
```
**Symbols:**

```
ffffffff810cb550-ffffffff810cb695: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cffc0)
Location: kernel/locking/rtmutex.c:1012
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810cffc0-ffffffff810d00f1: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d69b0)
Location: kernel/locking/rtmutex.c:1076
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_finish_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810d69b0-ffffffff810d6ae1: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5a40)
Location: kernel/locking/rtmutex.c:1080
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810d5a40-ffffffff810d5b90: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810dd9c0)
Location: kernel/locking/rtmutex.c:1068
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810dd9c0-ffffffff810ddb4b: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e6040)
Location: kernel/locking/rtmutex.c:1068
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810e6040-ffffffff810e61ad: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f15c0)
Location: kernel/locking/rtmutex.c:1068
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810f15c0-ffffffff810f1729: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f9e30)
Location: kernel/locking/rtmutex.c:1069
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810f9e30-ffffffff810f9ff9: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105c20)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81105c20-ffffffff81105de9: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110b40)
Location: kernel/locking/rtmutex.c:1065
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81110b40-ffffffff81110d3a: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110dcf0)
Location: kernel/locking/rtmutex.c:1065
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff8110dcf0-ffffffff8110deea: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c36df0)
Location: kernel/locking/rtmutex.c:1039
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff81c36df0-ffffffff81c370b0: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55360)
Location: kernel/locking/rtmutex.c:1408
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff81d55360-ffffffff81d5562b: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f26fc0)
Location: kernel/locking/rtmutex.c:1419
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff81f26fc0-ffffffff81f272c1: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d2a80)
Location: kernel/locking/rtmutex.c:1457
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff820d2a80-ffffffff820d2d81: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82156df0)
Location: kernel/locking/rtmutex.c:1515
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff82156df0-ffffffff821570da: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex_base *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82239c30)
Location: kernel/locking/rtmutex.c:1534
Inline: False
Direct callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex_api.c:rt_mutex_start_proxy_lock
```
**Symbols:**

```
ffffffff82239c30-ffffffff82239f1a: remove_waiter (STB_LOCAL)
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
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016bc80)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffff80001016bc80-ffff80001016bf08: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b769c)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
c03b769c-c03b78b8: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3790)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
c0000000001c3790-c0000000001c3a6c: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010bfda)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffe00010bfda-ffffffe00010c1ce: remove_waiter (STB_LOCAL)
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
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fef30)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810fef30-ffffffff810ff0f9: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef120)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810ef120-ffffffff810ef2e3: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc0f0)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff810fc0f0-ffffffff810fc2b9: remove_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_waiter(struct rt_mutex *lock, struct rt_mutex_waiter *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107330)
Location: kernel/locking/rtmutex.c:1067
Inline: False
Direct callers:
  - kernel/locking/rtmutex.c:rt_mutex_cleanup_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_start_proxy_lock
  - kernel/locking/rtmutex.c:rt_mutex_slowlock
```
**Symbols:**

```
ffffffff81107330-ffffffff811074f6: remove_waiter (STB_LOCAL)
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
