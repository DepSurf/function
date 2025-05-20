# Function: <code>wait_for_owner_exiting</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114a4f0)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8114a4f0-ffffffff8114a550: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115b010)
Location: kernel/futex.c:1131
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8115b010-ffffffff8115b088: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157130)
Location: kernel/futex.c:1128
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81157130-ffffffff811571a8: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158560)
Location: kernel/futex.c:1128
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81158560-ffffffff811585d8: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117d470)
Location: kernel/futex.c:1186
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8117d470-ffffffff8117d4e8: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b3180)
Location: kernel/futex/core.c:469
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811b3180-ffffffff811b3206: wait_for_owner_exiting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f4090)
Location: kernel/futex/core.c:469
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff811f4090-ffffffff811f4116: wait_for_owner_exiting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208820)
Location: kernel/futex/core.c:469
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff81208820-ffffffff812088a6: wait_for_owner_exiting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f6b0)
Location: kernel/futex/core.c:482
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff8121f6b0-ffffffff8121f736: wait_for_owner_exiting (STB_GLOBAL)
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
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b6910)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffff8000101b6910-ffff8000101b6990: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c04012b8)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
c04012b8-c0401384: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021c840)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
c00000000021c840-c00000000021c930: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013c58e)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffe00013c58e-ffffffe00013c60a: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142b10)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81142b10-ffffffff81142b70: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135e70)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff81135e70-ffffffff81135ed0: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811409c0)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff811409c0-ffffffff81140a20: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wait_for_owner_exiting(int ret, struct task_struct *exiting);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114dc20)
Location: kernel/futex.c:1202
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_requeue
```
**Symbols:**

```
ffffffff8114dc20-ffffffff8114dc80: wait_for_owner_exiting (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
