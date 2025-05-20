# Function: <code>futex_top_waiter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ff7d0)
Location: kernel/futex.c:655
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810ff7d0-ffffffff810ff82a: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81106bd0)
Location: kernel/futex.c:732
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81106bd0-ffffffff81106c2a: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e390)
Location: kernel/futex.c:741
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8110e390-ffffffff8110e3ea: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fb10)
Location: kernel/futex.c:744
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8110fb10-ffffffff8110fb60: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111ae00)
Location: kernel/futex.c:744
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8111ae00-ffffffff8111ae50: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81127b80)
Location: kernel/futex.c:744
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81127b80-ffffffff81127bd0: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133260)
Location: kernel/futex.c:752
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81133260-ffffffff811332b0: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e170)
Location: kernel/futex.c:767
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8113e170-ffffffff8113e1ca: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81149d00)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81149d00-ffffffff81149d5a: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115ae60)
Location: kernel/futex.c:716
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8115ae60-ffffffff8115aeb0: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81156f60)
Location: kernel/futex.c:694
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81156f60-ffffffff81156fb0: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158370)
Location: kernel/futex.c:693
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81158370-ffffffff811583c0: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d280)
Location: kernel/futex.c:751
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8117d280-ffffffff8117d2d0: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2c50)
Location: kernel/futex/core.c:429
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811b2c50-ffffffff811b2cc2: futex_top_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3b10)
Location: kernel/futex/core.c:429
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811f3b10-ffffffff811f3b82: futex_top_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff812082b0)
Location: kernel/futex/core.c:429
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff812082b0-ffffffff81208322: futex_top_waiter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f140)
Location: kernel/futex/core.c:442
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff8121f140-ffffffff8121f1b2: futex_top_waiter (STB_GLOBAL)
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
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b6460)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffff8000101b6460-ffff8000101b64f8: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400088)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c0400088-c0400118: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021dfc0)
Location: kernel/futex.c:788
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c00000000021bbf0-c00000000021bc84: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013df44)
Location: kernel/futex.c:788
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffe00013c1f0-ffffffe00013c262: futex_top_waiter (STB_LOCAL)
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
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142320)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81142320-ffffffff8114237a: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135680)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81135680-ffffffff811356da: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811401d0)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811401d0-ffffffff8114022a: futex_top_waiter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct futex_q *futex_top_waiter(struct futex_hash_bucket *hb, union futex_key *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114cd00)
Location: kernel/futex.c:788
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8114cd00-ffffffff8114cd5a: futex_top_waiter (STB_LOCAL)
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
