# Function: <code>cmpxchg_futex_value_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff810fffc0)
Location: kernel/futex.c:667
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
```
**Symbols:**

```
ffffffff810fffc0-ffffffff81100043: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81106fd0)
Location: kernel/futex.c:744
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81106fd0-ffffffff81107050: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e790)
Location: kernel/futex.c:753
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8110e790-ffffffff8110e810: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fba0)
Location: kernel/futex.c:756
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8110fba0-ffffffff8110fbf5: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111ae90)
Location: kernel/futex.c:756
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8111ae90-ffffffff8111aee8: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81127bd0)
Location: kernel/futex.c:756
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81127bd0-ffffffff81127c28: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811332b0)
Location: kernel/futex.c:764
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:do_futex
  - kernel/futex.c:do_futex
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811332b0-ffffffff81133308: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e350)
Location: kernel/futex.c:779
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8113e350-ffffffff8113e3ac: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81149ee0)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81149ee0-ffffffff81149f3c: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115acb0)
Location: kernel/futex.c:728
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8115acb0-ffffffff8115ad0c: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81156e00)
Location: kernel/futex.c:706
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81156e00-ffffffff81156e7b: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158230)
Location: kernel/futex.c:705
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81158230-ffffffff8115828f: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d140)
Location: kernel/futex.c:763
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8117d140-ffffffff8117d19f: cmpxchg_futex_value_locked (STB_LOCAL)
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
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b6d88)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffff8000101b6d88-ffff8000101b6f54: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400118)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c0400118-c04001d8: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021c770)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
c00000000021c770-c00000000021c838: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c2be)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:handle_futex_death
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffe00013c2be-ffffffe00013c344: cmpxchg_futex_value_locked (STB_LOCAL)
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
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142500)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81142500-ffffffff8114255c: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135860)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81135860-ffffffff811358bc: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811403b0)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811403b0-ffffffff8114040c: cmpxchg_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cmpxchg_futex_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114cee0)
Location: kernel/futex.c:800
Inline: False
Direct callers:
  - kernel/futex.c:futex_init
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8114cee0-ffffffff8114cf3c: cmpxchg_futex_value_locked (STB_LOCAL)
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
