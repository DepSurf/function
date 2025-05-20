# Function: <code>put_pi_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811071e0)
Location: kernel/futex.c:810
Inline: True
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff811071e0-ffffffff81107281: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e9a0)
Location: kernel/futex.c:819
Inline: True
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8110e9a0-ffffffff8110ea41: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81110a30)
Location: kernel/futex.c:827
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81110a30-ffffffff81110ad9: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b320)
Location: kernel/futex.c:825
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff8111b320-ffffffff8111b3f1: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811287b0)
Location: kernel/futex.c:825
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff811287b0-ffffffff81128880: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81134370)
Location: kernel/futex.c:833
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81134370-ffffffff81134440: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113f310)
Location: kernel/futex.c:848
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff8113f310-ffffffff8113f3f7: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114b2f0)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8114b2f0-ffffffff8114b3d7: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115c120)
Location: kernel/futex.c:797
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff8115c120-ffffffff8115c22e: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157af0)
Location: kernel/futex.c:798
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81157af0-ffffffff81157bbc: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158f30)
Location: kernel/futex.c:797
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff81158f30-ffffffff81158ffc: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117e5b0)
Location: kernel/futex.c:855
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:exit_pi_state_list
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff8117e5b0-ffffffff8117e6cc: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b4ba0)
Location: kernel/futex/pi.c:77
Inline: True
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811b4ba0-ffffffff811b4ce4: put_pi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f5c80)
Location: kernel/futex/pi.c:77
Inline: True
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811f5c80-ffffffff811f5dc4: put_pi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120a480)
Location: kernel/futex/pi.c:77
Inline: True
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff8120a480-ffffffff8120a5c4: put_pi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff812219e0)
Location: kernel/futex/pi.c:78
Inline: True
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff812219e0-ffffffff81221b24: put_pi_state (STB_GLOBAL)
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
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b7800)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffff8000101b7800-ffff8000101b7964: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400f18)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
c0400f18-c0401008: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021dc90)
Location: kernel/futex.c:869
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:unqueue_me_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
c00000000021dc90-c00000000021de3c: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013d2d6)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffe00013d2d6-ffffffe00013d402: put_pi_state (STB_LOCAL)
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
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81143910)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81143910-ffffffff811439f7: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136b00)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81136b00-ffffffff81136be1: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811417c0)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff811417c0-ffffffff811418a7: put_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114d550)
Location: kernel/futex.c:869
Inline: True
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8114d550-ffffffff8114d62c: put_pi_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
