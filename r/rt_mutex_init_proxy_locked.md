# Function: <code>rt_mutex_init_proxy_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cb890)
Location: kernel/locking/rtmutex.c:1555
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810cb890-ffffffff810cb8b5: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d02f0)
Location: kernel/locking/rtmutex.c:1564
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810d02f0-ffffffff810d0327: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6ce0)
Location: kernel/locking/rtmutex.c:1632
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810d6ce0-ffffffff810d6d17: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5cb0)
Location: kernel/locking/rtmutex.c:1682
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810d5cb0-ffffffff810d5ce7: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ddc70)
Location: kernel/locking/rtmutex.c:1681
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810ddc70-ffffffff810ddca7: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e62c0)
Location: kernel/locking/rtmutex.c:1702
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810e62c0-ffffffff810e62e5: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1840)
Location: kernel/locking/rtmutex.c:1702
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810f1840-ffffffff810f1865: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa130)
Location: kernel/locking/rtmutex.c:1703
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810fa130-ffffffff810fa167: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105f20)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff81105f20-ffffffff81105f57: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110e90)
Location: kernel/locking/rtmutex.c:1699
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff81110e90-ffffffff81110eb5: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110e040)
Location: kernel/locking/rtmutex.c:1699
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff8110e040-ffffffff8110e065: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c37550)
Location: kernel/locking/rtmutex.c:1579
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff81c37550-ffffffff81c37575: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex_base *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55d70)
Location: kernel/locking/rtmutex_api.c:214
Inline: False
Direct callers:
  - kernel/futex.c:__attach_to_pi_owner
```
**Symbols:**

```
ffffffff81d55d70-ffffffff81d55d95: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex_base *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27ca0)
Location: kernel/locking/rtmutex_api.c:236
Inline: False
Direct callers:
  - kernel/futex/pi.c:__attach_to_pi_owner
```
**Symbols:**

```
ffffffff81f27ca0-ffffffff81f27ce3: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex_base *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d37f0)
Location: kernel/locking/rtmutex_api.c:236
Inline: False
Direct callers:
  - kernel/futex/pi.c:__attach_to_pi_owner
```
**Symbols:**

```
ffffffff820d37f0-ffffffff820d383b: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex_base *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157a70)
Location: kernel/locking/rtmutex_api.c:236
Inline: False
Direct callers:
  - kernel/futex/pi.c:__attach_to_pi_owner
```
**Symbols:**

```
ffffffff82157a70-ffffffff82157abb: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex_base *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a8e0)
Location: kernel/locking/rtmutex_api.c:236
Inline: False
Direct callers:
  - kernel/futex/pi.c:__attach_to_pi_owner
```
**Symbols:**

```
ffffffff8223a8e0-ffffffff8223a92b: rt_mutex_init_proxy_locked (STB_GLOBAL)
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
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016c120)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffff80001016c120-ffff80001016c154: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7a24)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
c03b7a24-c03b7a5c: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3c80)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
c0000000001c3c80-c0000000001c3cb4: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c31c)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffe00010c31c-ffffffe00010c35a: rt_mutex_init_proxy_locked (STB_GLOBAL)
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
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff230)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810ff230-ffffffff810ff267: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef420)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810ef420-ffffffff810ef457: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc3f0)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff810fc3f0-ffffffff810fc427: rt_mutex_init_proxy_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_mutex_init_proxy_locked(struct rt_mutex *lock, struct task_struct *proxy_owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107620)
Location: kernel/locking/rtmutex.c:1701
Inline: False
Direct callers:
  - kernel/futex.c:attach_to_pi_owner
```
**Symbols:**

```
ffffffff81107620-ffffffff81107657: rt_mutex_init_proxy_locked (STB_GLOBAL)
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
