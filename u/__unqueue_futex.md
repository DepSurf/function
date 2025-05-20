# Function: <code>__unqueue_futex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ff930)
Location: kernel/futex.c:1164
Inline: False
Direct callers:
  - kernel/futex.c:mark_wake_futex
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff810ff930-ffffffff810ff98a: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81106d40)
Location: kernel/futex.c:1244
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81106d40-ffffffff81106d9d: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e500)
Location: kernel/futex.c:1253
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8110e500-ffffffff8110e55d: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fc70)
Location: kernel/futex.c:1351
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8110fc70-ffffffff8110fcaf: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111af60)
Location: kernel/futex.c:1382
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8111af60-ffffffff8111af9f: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81127e20)
Location: kernel/futex.c:1364
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81127e20-ffffffff81127e5e: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133640)
Location: kernel/futex.c:1429
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81133640-ffffffff81133678: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:1446
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8113e5c0-ffffffff8113e5f9: __unqueue_futex (STB_LOCAL)
ffffffff81142919-ffffffff8114293f: __unqueue_futex.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114a150)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8114a150-ffffffff8114a189: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a8f0)
Location: kernel/futex.c:1450
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8115a8f0-ffffffff8115a92f: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81156920)
Location: kernel/futex.c:1447
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81156920-ffffffff8115695f: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157d40)
Location: kernel/futex.c:1447
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81157d40-ffffffff81157d7f: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117cbc0)
Location: kernel/futex.c:1506
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8117cbc0-ffffffff8117cbfb: __unqueue_futex (STB_LOCAL)
```
</details>
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
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b6b08)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffff8000101b6b08-ffff8000101b6b94: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c040032c)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
c040032c-c04003a0: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021bdf0)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:unqueue_me_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
c00000000021bdf0-c00000000021be84: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c3a8)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffe00013c3a8-ffffffe00013c404: __unqueue_futex (STB_LOCAL)
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
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142770)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81142770-ffffffff811427a9: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135ad0)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81135ad0-ffffffff81135b09: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140620)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff81140620-ffffffff81140659: __unqueue_futex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unqueue_futex(struct futex_q *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114d2b0)
Location: kernel/futex.c:1521
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:mark_wake_futex
```
**Symbols:**

```
ffffffff8114d2b0-ffffffff8114d2e9: __unqueue_futex (STB_LOCAL)
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
