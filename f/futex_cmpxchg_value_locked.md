# Function: <code>futex_cmpxchg_value_locked</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int futex_cmpxchg_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2cd0)
Location: kernel/futex/core.c:440
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811b2cd0-ffffffff811b2d3d: futex_cmpxchg_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_cmpxchg_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3ba0)
Location: kernel/futex/core.c:440
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff811f3ba0-ffffffff811f3c0d: futex_cmpxchg_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_cmpxchg_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208340)
Location: kernel/futex/core.c:440
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81208340-ffffffff81208398: futex_cmpxchg_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_cmpxchg_value_locked(u32 *curval, u32 *uaddr, u32 uval, u32 newval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f1d0)
Location: kernel/futex/core.c:453
Inline: False
Direct callers:
  - kernel/futex/core.c:handle_futex_death
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:futex_lock_pi_atomic
  - kernel/futex/pi.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8121f1d0-ffffffff8121f228: futex_cmpxchg_value_locked (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
