# Function: <code>rt_mutex_next_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cb970)
Location: kernel/locking/rtmutex.c:1642
Inline: False
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810cb970-ffffffff810cb996: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d03f0)
Location: kernel/locking/rtmutex.c:1651
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff810d03f0-ffffffff810d0418: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6de0)
Location: kernel/locking/rtmutex.c:1723
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff810d6de0-ffffffff810d6e08: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5dd0)
Location: kernel/locking/rtmutex.c:1778
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810d5dd0-ffffffff810d5df8: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ddd90)
Location: kernel/locking/rtmutex.c:1777
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810ddd90-ffffffff810dddb6: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e63e0)
Location: kernel/locking/rtmutex.c:1798
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810e63e0-ffffffff810e640b: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1960)
Location: kernel/locking/rtmutex.c:1824
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810f1960-ffffffff810f198b: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa260)
Location: kernel/locking/rtmutex.c:1825
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810fa260-ffffffff810fa28d: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81106050)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81106050-ffffffff8110607d: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110fe0)
Location: kernel/locking/rtmutex.c:1821
Inline: False
Direct callers:
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff81110fe0-ffffffff81111009: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110e190)
Location: kernel/locking/rtmutex.c:1820
Inline: False
Direct callers:
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff8110e190-ffffffff8110e1b9: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016c2e8)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffff80001016c2e8-ffff80001016c340: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7b5c)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
c03b7b5c-c03b7ba8: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3e80)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
c0000000001c3e80-c0000000001c3ec8: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c48a)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffe00010c48a-ffffffe00010c4c8: rt_mutex_next_owner (STB_GLOBAL)
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
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff360)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810ff360-ffffffff810ff38d: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef550)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810ef550-ffffffff810ef57d: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc520)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff810fc520-ffffffff810fc54d: rt_mutex_next_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *rt_mutex_next_owner(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107750)
Location: kernel/locking/rtmutex.c:1823
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81107750-ffffffff8110777d: rt_mutex_next_owner (STB_GLOBAL)
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
