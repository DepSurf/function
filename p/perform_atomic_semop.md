# Function: <code>perform_atomic_semop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81326fc0)
Location: ipc/sem.c:613
Inline: True
Direct callers:
  - ipc/sem.c:wake_const_ops
  - ipc/sem.c:update_queue
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff81326fc0-ffffffff81327138: perform_atomic_semop.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff8135bab0)
Location: ipc/sem.c:609
Inline: True
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff8135bab0-ffffffff8135bc10: perform_atomic_semop.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81372030)
Location: ipc/sem.c:655
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81372030-ffffffff813722d1: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81385280)
Location: ipc/sem.c:666
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81385280-ffffffff81385531: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813a9b00)
Location: ipc/sem.c:669
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff813a9b00-ffffffff813a9db1: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9710)
Location: ipc/sem.c:703
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff813d9710-ffffffff813d9a4b: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f3f50)
Location: ipc/sem.c:702
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff813f3f50-ffffffff813f428b: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81420220)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81420220-ffffffff814204f3: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143a020)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff8143a020-ffffffff8143a2e6: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148a4d0)
Location: ipc/sem.c:717
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff8148a4d0-ffffffff8148a6a0: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a7a80)
Location: ipc/sem.c:716
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff814a7a80-ffffffff814a7c50: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814ad9c0)
Location: ipc/sem.c:716
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff814ad9c0-ffffffff814adb8c: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:719
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81505ea0-ffffffff81506082: perform_atomic_semop (STB_LOCAL)
ffffffff81cd2ac7-ffffffff81cd2ae3: perform_atomic_semop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:719
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81597d40-ffffffff81597f66: perform_atomic_semop (STB_LOCAL)
ffffffff81e85c39-ffffffff81e85c55: perform_atomic_semop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:719
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81640f30-ffffffff81641156: perform_atomic_semop (STB_LOCAL)
ffffffff82072db2-ffffffff82072dce: perform_atomic_semop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:719
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff816794c0-ffffffff816796e6: perform_atomic_semop (STB_LOCAL)
ffffffff820f2a07-ffffffff820f2a23: perform_atomic_semop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:719
Inline: False
Direct callers:
  - ipc/sem.c:__do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff816b56b0-ffffffff816b5a8c: perform_atomic_semop (STB_LOCAL)
ffffffff821cfcb7-ffffffff821cfcd3: perform_atomic_semop.cold (STB_LOCAL)
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
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105216d8)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffff8000105216d8-ffff8000105219e0: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dc894)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
c06dc894-c06dcb74: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066b2f0)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
c00000000066b2f0-c00000000066b72c: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000387134)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffe000387134-ffffffe0003873b4: perform_atomic_semop (STB_LOCAL)
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
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81432600)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81432600-ffffffff814328c6: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423080)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81423080-ffffffff81423346: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142e7a0)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff8142e7a0-ffffffff8142ea66: perform_atomic_semop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perform_atomic_semop(struct sem_array *sma, struct sem_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81445a90)
Location: ipc/sem.c:698
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:update_queue
  - ipc/sem.c:wake_const_ops
```
**Symbols:**

```
ffffffff81445a90-ffffffff81445d56: perform_atomic_semop (STB_LOCAL)
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
