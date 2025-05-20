# Function: <code>fault_in_user_writeable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ff8d0)
Location: kernel/futex.c:635
Inline: False
Direct callers:
  - kernel/futex.c:futex_wake_op
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810ff8d0-ffffffff810ff92f: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81106cd0)
Location: kernel/futex.c:712
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81106cd0-ffffffff81106d32: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e490)
Location: kernel/futex.c:721
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8110e490-ffffffff8110e4f2: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fc00)
Location: kernel/futex.c:724
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8110fc00-ffffffff8110fc62: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111aef0)
Location: kernel/futex.c:724
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8111aef0-ffffffff8111af52: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81127db0)
Location: kernel/futex.c:724
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81127db0-ffffffff81127e12: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811335d0)
Location: kernel/futex.c:732
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff811335d0-ffffffff81133632: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e550)
Location: kernel/futex.c:747
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8113e550-ffffffff8113e5b6: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114a0e0)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8114a0e0-ffffffff8114a146: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115c673)
Location: kernel/futex.c:696
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81156ca0)
Location: kernel/futex.c:674
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81156ca0-ffffffff81156d3a: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811580b0)
Location: kernel/futex.c:673
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff811580b0-ffffffff81158152: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117cfe0)
Location: kernel/futex.c:731
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8117cfe0-ffffffff8117d06b: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2bb0)
Location: kernel/futex/core.c:409
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff811b2bb0-ffffffff811b2c43: fault_in_user_writeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3a60)
Location: kernel/futex/core.c:409
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff811f3a60-ffffffff811f3af3: fault_in_user_writeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208200)
Location: kernel/futex/core.c:409
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff81208200-ffffffff81208296: fault_in_user_writeable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f090)
Location: kernel/futex/core.c:422
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
```
**Symbols:**

```
ffffffff8121f090-ffffffff8121f126: fault_in_user_writeable (STB_GLOBAL)
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
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b65a8)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffff8000101b65a8-ffff8000101b6614: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c04002b0)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
c04002b0-c040032c: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021bd50)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
c00000000021bd50-c00000000021bdec: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c344)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffe00013c344-ffffffe00013c3a8: fault_in_user_writeable (STB_LOCAL)
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
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142700)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81142700-ffffffff81142766: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135a60)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff81135a60-ffffffff81135ac6: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811405b0)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff811405b0-ffffffff81140616: fault_in_user_writeable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fault_in_user_writeable(u32 *uaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114d240)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_wake_op
```
**Symbols:**

```
ffffffff8114d240-ffffffff8114d2a6: fault_in_user_writeable (STB_LOCAL)
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
