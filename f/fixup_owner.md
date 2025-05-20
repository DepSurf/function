# Function: <code>fixup_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811008d0)
Location: kernel/futex.c:2097
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff811008d0-ffffffff811009ba: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811074b0)
Location: kernel/futex.c:2221
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff811074b0-ffffffff811075b4: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110ec70)
Location: kernel/futex.c:2230
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8110ec70-ffffffff8110ed75: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111270)
Location: kernel/futex.c:2341
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81111270-ffffffff811112d8: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111b6c0)
Location: kernel/futex.c:2469
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8111b6c0-ffffffff8111b738: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2451
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81128c60-ffffffff81128cca: fixup_owner (STB_LOCAL)
ffffffff8112bab8-ffffffff8112bad2: fixup_owner.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2519
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81134d60-ffffffff81134dca: fixup_owner (STB_LOCAL)
ffffffff81137992-ffffffff811379ac: fixup_owner.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2550
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81140140-ffffffff811401ac: fixup_owner (STB_LOCAL)
ffffffff811429ec-ffffffff81142a03: fixup_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8114bd30-ffffffff8114bd9c: fixup_owner (STB_LOCAL)
ffffffff8114e644-ffffffff8114e65b: fixup_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2555
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8115ca30-ffffffff8115ca98: fixup_owner (STB_LOCAL)
ffffffff8115eee1-ffffffff8115eef8: fixup_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158fe0)
Location: kernel/futex.c:2536
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81158fe0-ffffffff8115907e: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115a570)
Location: kernel/futex.c:2535
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8115a570-ffffffff8115a60e: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117ef80)
Location: kernel/futex.c:2783
Inline: True
Direct callers:
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8117ef80-ffffffff8117f01e: fixup_owner (STB_LOCAL)
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
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b9b20)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffff8000101b9b20-ffff8000101b9bc8: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0400b50)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c0400b50-c0400bdc: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021ffe0)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
c00000000021ffe0-c0000000002200d8: fixup_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013ddf6)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffe00013ddf6-ffffffe00013de7a: fixup_owner (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81144350-ffffffff811443bc: fixup_owner (STB_LOCAL)
ffffffff81146c64-ffffffff81146c7b: fixup_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81137370-ffffffff811373dc: fixup_owner (STB_LOCAL)
ffffffff81139f64-ffffffff81139f7b: fixup_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff81142200-ffffffff8114226c: fixup_owner (STB_LOCAL)
ffffffff81144b14-ffffffff81144b2b: fixup_owner.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fixup_owner(u32 *uaddr, struct futex_q *q, int locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2642
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:futex_lock_pi
```
**Symbols:**

```
ffffffff8114d950-ffffffff8114d9bc: fixup_owner (STB_LOCAL)
ffffffff8115167c-ffffffff81151693: fixup_owner.cold (STB_LOCAL)
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
