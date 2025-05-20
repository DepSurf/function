# Function: <code>wake_futex_pi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81102c6a)
Location: kernel/futex.c:1206
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8110a042)
Location: kernel/futex.c:1286
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81111832)
Location: kernel/futex.c:1295
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81112fe4)
Location: kernel/futex.c:1396
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111e576)
Location: kernel/futex.c:1427
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112b096)
Location: kernel/futex.c:1409
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81136f06)
Location: kernel/futex.c:1477
Inline: True
Inline callers:
  - kernel/futex.c:do_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113fbed)
Location: kernel/futex.c:1493
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114b7cd)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wake_futex_pi(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115be40)
Location: kernel/futex.c:1497
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff8115be40-ffffffff8115bfe1: wake_futex_pi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wake_futex_pi(u32 *uaddr, u32 uval, struct futex_pi_state *pi_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157c00)
Location: kernel/futex.c:1494
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
```
**Symbols:**

```
ffffffff81157c00-ffffffff81157d11: wake_futex_pi (STB_LOCAL)
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
In kernel/futex.c (ffffffff81159c2d)
Location: kernel/futex.c:1494
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
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
In kernel/futex.c (ffffffff8117ea3f)
Location: kernel/futex.c:1553
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
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
In kernel/futex/pi.c (ffffffff811b5741)
Location: kernel/futex/pi.c:613
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
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
In kernel/futex/pi.c (ffffffff811f6861)
Location: kernel/futex/pi.c:613
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
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
In kernel/futex/pi.c (ffffffff8120b053)
Location: kernel/futex/pi.c:613
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
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
In kernel/futex/pi.c (ffffffff81222626)
Location: kernel/futex/pi.c:614
Inline: True
Inline callers:
  - kernel/futex/pi.c:futex_unlock_pi
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b8a4c)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c0402034)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021e08c)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013dee8)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81143ded)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811378dd)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81141c9d)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114f259)
Location: kernel/futex.c:1568
Inline: True
Inline callers:
  - kernel/futex.c:futex_unlock_pi
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
