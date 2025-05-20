# Function: <code>attach_to_pi_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int attach_to_pi_state(u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810ff830)
Location: kernel/futex.c:892
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff810ff830-ffffffff810ff8c4: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int attach_to_pi_state(u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81106c30)
Location: kernel/futex.c:972
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81106c30-ffffffff81106cc4: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int attach_to_pi_state(u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e3f0)
Location: kernel/futex.c:981
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8110e3f0-ffffffff8110e484: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111870)
Location: kernel/futex.c:1024
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81111870-ffffffff8111198f: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111c5e0)
Location: kernel/futex.c:1051
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8111c5e0-ffffffff8111c6ff: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811288c0)
Location: kernel/futex.c:1033
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811288c0-ffffffff811289df: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81134860)
Location: kernel/futex.c:1041
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81134860-ffffffff8113497f: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:1056
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8113f840-ffffffff8113f964: attach_to_pi_state (STB_LOCAL)
ffffffff8114297d-ffffffff81142990: attach_to_pi_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114b420)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8114b420-ffffffff8114b54b: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115bff0)
Location: kernel/futex.c:1006
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8115bff0-ffffffff8115c11b: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158790)
Location: kernel/futex.c:1003
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81158790-ffffffff811588a6: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159a00)
Location: kernel/futex.c:1003
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81159a00-ffffffff81159b16: attach_to_pi_state (STB_LOCAL)
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
In kernel/futex.c (ffffffff8117f13b)
Location: kernel/futex.c:1061
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
In kernel/futex/pi.c (ffffffff811b4e1c)
Location: kernel/futex/pi.c:202
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
In kernel/futex/pi.c (ffffffff811f5f0c)
Location: kernel/futex/pi.c:202
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
In kernel/futex/pi.c (ffffffff8120a70c)
Location: kernel/futex/pi.c:202
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
In kernel/futex/pi.c (ffffffff81221c6c)
Location: kernel/futex/pi.c:203
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
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b95b8)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffff8000101b95b8-ffff8000101b9740: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400db8)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c0400db8-c0400f18: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021ec00)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c00000000021ec00-c00000000021ee2c: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013d908)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffe00013d908-ffffffe00013da4a: attach_to_pi_state (STB_LOCAL)
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
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81143a40)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81143a40-ffffffff81143b6b: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136870)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81136870-ffffffff8113698f: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811418f0)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811418f0-ffffffff81141a1b: attach_to_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int attach_to_pi_state(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state, struct futex_pi_state **ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114d120)
Location: kernel/futex.c:1078
Inline: False
Direct callers:
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8114d120-ffffffff8114d23a: attach_to_pi_state (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *uaddr</code>
</li>
<li>
<b>Param reordered. </b>
<code>uval, pi_state, ps</code> ➡️ <code>uaddr, uval, pi_state, ps</code>
</li>
</ul>
</details>
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
