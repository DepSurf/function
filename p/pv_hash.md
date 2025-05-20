# Function: <code>pv_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810ca850)
Location: kernel/locking/qspinlock_paravirt.h:99
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810ca850-ffffffff810ca8fa: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810cf270)
Location: kernel/locking/qspinlock_paravirt.h:203
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810cf270-ffffffff810cf317: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810d5c60)
Location: kernel/locking/qspinlock_paravirt.h:206
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810d5c60-ffffffff810d5d07: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810d4be0)
Location: kernel/locking/qspinlock_paravirt.h:207
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810d4be0-ffffffff810d4c87: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810dc990)
Location: kernel/locking/qspinlock_paravirt.h:237
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810dc990-ffffffff810dca37: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810e4fd0)
Location: kernel/locking/qspinlock_paravirt.h:214
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810e4fd0-ffffffff810e5077: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810f05b0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810f05b0-ffffffff810f0657: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810f8e00)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810f8e00-ffffffff810f8e99: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff81104c10)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff81104c10-ffffffff81104ca9: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff8110f870)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:pv_wait_head_or_lock
```
**Symbols:**

```
ffffffff8110f870-ffffffff8110f90b: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff8110ca30)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:pv_wait_head_or_lock
```
**Symbols:**

```
ffffffff8110ca30-ffffffff8110cacb: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff8110e7e0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff8110e7e0-ffffffff8110e87b: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/qspinlock.c (0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff8112df70-ffffffff8112e041: pv_hash (STB_LOCAL)
ffffffff81ca95c5-ffffffff81ca9641: pv_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/qspinlock.c (0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff8114efd0-ffffffff8114f0ad: pv_hash (STB_LOCAL)
ffffffff81e595b8-ffffffff81e59634: pv_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/qspinlock.c (0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff8117e1d0-ffffffff8117e2ad: pv_hash (STB_LOCAL)
ffffffff82058283-ffffffff820582ff: pv_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/qspinlock.c (0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff8118ee70-ffffffff8118ef49: pv_hash (STB_LOCAL)
ffffffff820d6b7b-ffffffff820d6bd9: pv_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/locking/qspinlock.c (0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: False
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff8119d820-ffffffff8119d8f9: pv_hash (STB_LOCAL)
ffffffff821b1e11-ffffffff821b1e6f: pv_hash.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810fdf20)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810fdf20-ffffffff810fdfb9: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810ee120)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810ee120-ffffffff810ee1b9: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff810fb0e0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff810fb0e0-ffffffff810fb179: pv_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct qspinlock **pv_hash(struct qspinlock *lock, struct pv_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/qspinlock.c (ffffffff811062b0)
Location: kernel/locking/qspinlock_paravirt.h:212
Inline: True
Direct callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
  - kernel/locking/qspinlock.c:__pv_queued_spin_lock_slowpath
```
**Symbols:**

```
ffffffff811062b0-ffffffff81106349: pv_hash (STB_LOCAL)
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
