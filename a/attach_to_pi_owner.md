# Function: <code>attach_to_pi_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81101590)
Location: kernel/futex.c:963
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81101590-ffffffff81101737: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81108af0)
Location: kernel/futex.c:1043
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81108af0-ffffffff81108c8b: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811102e0)
Location: kernel/futex.c:1052
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811102e0-ffffffff8111047b: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811108b0)
Location: kernel/futex.c:1146
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811108b0-ffffffff81110a2d: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111c700)
Location: kernel/futex.c:1173
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8111c700-ffffffff8111c87d: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81128cd0)
Location: kernel/futex.c:1155
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81128cd0-ffffffff81128e3d: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133f10)
Location: kernel/futex.c:1217
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81133f10-ffffffff81134103: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:1232
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8113ee60-ffffffff8113f057: attach_to_pi_owner (STB_LOCAL)
ffffffff81142957-ffffffff8114297d: attach_to_pi_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114acd0)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8114acd0-ffffffff8114aef2: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115caa0)
Location: kernel/futex.c:1215
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8115caa0-ffffffff8115cd1d: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158a90)
Location: kernel/futex.c:1212
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81158a90-ffffffff81158d11: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159df0)
Location: kernel/futex.c:1212
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81159df0-ffffffff8115a071: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117f1db)
Location: kernel/futex.c:1300
Inline: True
Inline callers:
  - kernel/futex.c:futex_lock_pi_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b4ee8)
Location: kernel/futex/pi.c:410
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f5fd8)
Location: kernel/futex/pi.c:410
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120a7d8)
Location: kernel/futex/pi.c:410
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff81221d38)
Location: kernel/futex/pi.c:411
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_lock_pi_atomic
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
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b9bc8)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffff8000101b9bc8-ffff8000101b9e1c: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0401384)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c0401384-c04015e8: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021d930)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c00000000021d930-c00000000021dc8c: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013e312)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffe00013e312-ffffffe00013e52e: attach_to_pi_owner (STB_LOCAL)
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
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811432f0)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811432f0-ffffffff81143512: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136650)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81136650-ffffffff81136866: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811411a0)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811411a0-ffffffff811413c2: attach_to_pi_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int attach_to_pi_owner(u32 *uaddr, u32 uval, union futex_key *key, struct futex_pi_state **ps, struct task_struct **exiting);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114fa90)
Location: kernel/futex.c:1286
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8114fa90-ffffffff8114fcb1: attach_to_pi_owner (STB_LOCAL)
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
<b>Param added. </b>
<code>u32 *uaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>uval, key, ps</code> ➡️ <code>uaddr, uval, key, ps</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct **exiting</code>
</li>
</ul>
</details>
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
