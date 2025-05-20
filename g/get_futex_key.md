# Function: <code>get_futex_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ffa20)
Location: kernel/futex.c:468
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810ffa20-ffffffff810ffcb7: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811075c0)
Location: kernel/futex.c:489
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff811075c0-ffffffff811079bf: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110ed80)
Location: kernel/futex.c:498
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8110ed80-ffffffff8110f1ac: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81110020)
Location: kernel/futex.c:500
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff81110020-ffffffff81110350: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b740)
Location: kernel/futex.c:500
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8111b740-ffffffff8111baec: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, int rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81128260)
Location: kernel/futex.c:500
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff81128260-ffffffff81128623: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133b40)
Location: kernel/futex.c:508
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff81133b40-ffffffff81133f05: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113eab0)
Location: kernel/futex.c:523
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8113eab0-ffffffff8113ee5d: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114a550)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8114a550-ffffffff8114a8ff: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b090)
Location: kernel/futex.c:504
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8115b090-ffffffff8115b421: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, bool fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811571b0)
Location: kernel/futex.c:485
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff811571b0-ffffffff81157565: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, bool fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811585e0)
Location: kernel/futex.c:484
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff811585e0-ffffffff811589b4: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, bool fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d4f0)
Location: kernel/futex.c:542
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8117d4f0-ffffffff8117d8a9: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, bool fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2590)
Location: kernel/futex/core.c:220
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff811b2590-ffffffff811b2bab: get_futex_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, bool fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3430)
Location: kernel/futex/core.c:220
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff811f3430-ffffffff811f3a4b: get_futex_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, bool fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81207bb0)
Location: kernel/futex/core.c:220
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff81207bb0-ffffffff812081e5: get_futex_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, unsigned int flags, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121edc0)
Location: kernel/futex/core.c:221
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff8121edc0-ffffffff8121f080: get_futex_key (STB_GLOBAL)
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
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b79b8)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffff8000101b79b8-ffff8000101b7dd0: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0401764)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
c0401764-c0401b8c: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021cdd0)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
c00000000021cdd0-c00000000021d410: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c738)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffe00013c738-ffffffe00013ca5a: get_futex_key (STB_LOCAL)
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
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142b70)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff81142b70-ffffffff81142f1f: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135ed0)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff81135ed0-ffffffff8113627f: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140a20)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff81140a20-ffffffff81140dcf: get_futex_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_futex_key(u32 *uaddr, int fshared, union futex_key *key, enum futex_access rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114dc80)
Location: kernel/futex.c:572
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_wake
```
**Symbols:**

```
ffffffff8114dc80-ffffffff8114e02a: get_futex_key (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int rw</code> ➡️ <code>enum futex_access rw</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int fshared</code> ➡️ <code>bool fshared</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool fshared</code>
</li>
</ul>
</details>
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
