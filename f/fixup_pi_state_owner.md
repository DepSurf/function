# Function: <code>fixup_pi_state_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff811006f0)
Location: kernel/futex.c:1988
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff811006f0-ffffffff811008c6: fixup_pi_state_owner.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff811072d0)
Location: kernel/futex.c:2112
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff811072d0-ffffffff811074a6: fixup_pi_state_owner.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8110ea90)
Location: kernel/futex.c:2121
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff8110ea90-ffffffff8110ec66: fixup_pi_state_owner.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81111070)
Location: kernel/futex.c:2216
Inline: True
```
**Symbols:**

```
ffffffff81111070-ffffffff81111270: fixup_pi_state_owner.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8111b440)
Location: kernel/futex.c:2300
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff8111b440-ffffffff8111b6c0: fixup_pi_state_owner.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff811289e0)
Location: kernel/futex.c:2282
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff811289e0-ffffffff81128c52: fixup_pi_state_owner.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81134ae0)
Location: kernel/futex.c:2350
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff81134ae0-ffffffff81134d52: fixup_pi_state_owner.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (0)
Location: kernel/futex.c:2364
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff8113fe50-ffffffff81140137: fixup_pi_state_owner.isra.0 (STB_LOCAL)
ffffffff811429b6-ffffffff811429ec: fixup_pi_state_owner.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8114ba40)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff8114ba40-ffffffff8114bd2e: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115c710)
Location: kernel/futex.c:2369
Inline: False
Direct callers:
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff8115c710-ffffffff8115ca23: fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157fd0)
Location: kernel/futex.c:2505
Inline: True
```
**Symbols:**

```
ffffffff81157fd0-ffffffff81158029: fixup_pi_state_owner (STB_LOCAL)
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
In kernel/futex.c (ffffffff8115a5a4)
Location: kernel/futex.c:2504
Inline: True
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
In kernel/futex.c (ffffffff8117efb4)
Location: kernel/futex.c:2752
Inline: True
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
In kernel/futex/pi.c (ffffffff811b5148)
Location: kernel/futex/pi.c:855
Inline: True
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
In kernel/futex/pi.c (ffffffff811f6248)
Location: kernel/futex/pi.c:855
Inline: True
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
In kernel/futex/pi.c (ffffffff8120aa48)
Location: kernel/futex/pi.c:855
Inline: True
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
In kernel/futex/pi.c (ffffffff81221fa8)
Location: kernel/futex/pi.c:843
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffff8000101b9740)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffff8000101b9740-ffff8000101b9b1c: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c040079c)
Location: kernel/futex.c:2456
Inline: False
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
c040079c-c0400b50: fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (c00000000021fb40)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
c00000000021fb40-c00000000021ffdc: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffe00013da4a)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffe00013da4a-ffffffe00013ddf6: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81144060)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff81144060-ffffffff8114434e: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81137090)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff81137090-ffffffff8113736c: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81141f10)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff81141f10-ffffffff811421fe: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8114d670)
Location: kernel/futex.c:2456
Inline: True
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:fixup_owner
```
**Symbols:**

```
ffffffff8114d670-ffffffff8114d941: fixup_pi_state_owner.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
