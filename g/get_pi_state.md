# Function: <code>get_pi_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fe30)
Location: kernel/futex.c:816
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
  - kernel/futex.c:exit_pi_state_list
```
**Symbols:**

```
ffffffff8110fe30-ffffffff8110fe63: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b120)
Location: kernel/futex.c:816
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8111b120-ffffffff8111b153: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81127eb0)
Location: kernel/futex.c:816
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81127eb0-ffffffff81127ee3: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133680)
Location: kernel/futex.c:824
Inline: True
Direct callers:
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81133680-ffffffff811336b3: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e270)
Location: kernel/futex.c:839
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8113e270-ffffffff8113e2a5: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81149e00)
Location: kernel/futex.c:860
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81149e00-ffffffff81149e35: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115ae20)
Location: kernel/futex.c:788
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8115ae20-ffffffff8115ae5b: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81156f20)
Location: kernel/futex.c:789
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81156f20-ffffffff81156f5b: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158330)
Location: kernel/futex.c:788
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81158330-ffffffff81158367: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d240)
Location: kernel/futex.c:846
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8117d240-ffffffff8117d277: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b4b30)
Location: kernel/futex/pi.c:68
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811b4b30-ffffffff811b4b96: get_pi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f5c00)
Location: kernel/futex/pi.c:68
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811f5c00-ffffffff811f5c66: get_pi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120a400)
Location: kernel/futex/pi.c:68
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff8120a400-ffffffff8120a461: get_pi_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff81221960)
Location: kernel/futex/pi.c:69
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff81221960-ffffffff812219c1: get_pi_state (STB_GLOBAL)
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
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b67c8)
Location: kernel/futex.c:860
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffff8000101b67c8-ffff8000101b680c: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400d60)
Location: kernel/futex.c:860
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
c0400d60-c0400db8: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021c150)
Location: kernel/futex.c:860
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
c00000000021c150-c00000000021c198: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c482)
Location: kernel/futex.c:860
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffe00013c482-ffffffe00013c4d0: get_pi_state (STB_LOCAL)
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
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142420)
Location: kernel/futex.c:860
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81142420-ffffffff81142455: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135780)
Location: kernel/futex.c:860
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81135780-ffffffff811357b5: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811402d0)
Location: kernel/futex.c:860
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff811402d0-ffffffff81140305: get_pi_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void get_pi_state(struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114ce00)
Location: kernel/futex.c:860
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8114ce00-ffffffff8114ce35: get_pi_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
