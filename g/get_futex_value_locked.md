# Function: <code>get_futex_value_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81100170)
Location: kernel/futex.c:679
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81100170-ffffffff811001d2: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81107170)
Location: kernel/futex.c:756
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff81107170-ffffffff811071d2: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110e930)
Location: kernel/futex.c:765
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
```
**Symbols:**

```
ffffffff8110e930-ffffffff8110e992: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110fb60)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8110fb60-ffffffff8110fb98: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111ae50)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8111ae50-ffffffff8111ae8b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81127c30)
Location: kernel/futex.c:768
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81127c30-ffffffff81127c6b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133310)
Location: kernel/futex.c:776
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81133310-ffffffff8113334b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e3b0)
Location: kernel/futex.c:791
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8113e3b0-ffffffff8113e3eb: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81149f40)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81149f40-ffffffff81149f7b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a750)
Location: kernel/futex.c:740
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8115a750-ffffffff8115a78b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811575dc)
Location: kernel/futex.c:718
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158a2c)
Location: kernel/futex.c:717
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
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
In kernel/futex.c (ffffffff8117d91c)
Location: kernel/futex.c:775
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:futex_lock_pi_atomic
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
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b8dd8)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffff8000101b8dd8-ffff8000101b8f8c: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c04001d8)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:fixup_pi_state_owner
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
c04001d8-c0400258: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021c930)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
c00000000021c930-c00000000021c9d4: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c262)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffe00013c262-ffffffe00013c2be: get_futex_value_locked (STB_LOCAL)
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
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142560)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81142560-ffffffff8114259b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811358c0)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff811358c0-ffffffff811358fb: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140410)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff81140410-ffffffff8114044b: get_futex_value_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_futex_value_locked(u32 *dest, u32 *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114cf40)
Location: kernel/futex.c:812
Inline: False
Direct callers:
  - kernel/futex.c:futex_wait_setup
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_requeue
  - kernel/futex.c:futex_lock_pi_atomic
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_owner
  - kernel/futex.c:attach_to_pi_state
```
**Symbols:**

```
ffffffff8114cf40-ffffffff8114cf7b: get_futex_value_locked (STB_LOCAL)
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
