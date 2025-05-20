# Function: <code>__sigqueue_free</code>

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
In kernel/signal.c (ffffffff8108ce40)
Location: kernel/signal.c:395
Inline: True
Inline callers:
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:sigqueue_free
Direct callers:
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:sigqueue_free
```
**Symbols:**

```
ffffffff8108ce40-ffffffff8108ce76: __sigqueue_free.part.15 (STB_LOCAL)
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
In kernel/signal.c (ffffffff81092daa)
Location: kernel/signal.c:395
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff81090010-ffffffff81090046: __sigqueue_free.part.17 (STB_LOCAL)
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
In kernel/signal.c (ffffffff81097d3a)
Location: kernel/signal.c:395
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff81094f90-ffffffff81094fc6: __sigqueue_free.part.20 (STB_LOCAL)
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
In kernel/signal.c (ffffffff8109504a)
Location: kernel/signal.c:401
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff81092020-ffffffff81092056: __sigqueue_free.part.20 (STB_LOCAL)
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
In kernel/signal.c (ffffffff8109beea)
Location: kernel/signal.c:403
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff81098eb0-ffffffff81098ee6: __sigqueue_free.part.20 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a02ba)
Location: kernel/signal.c:405
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff8109c6d0-ffffffff8109c706: __sigqueue_free.part.34 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810a8e64)
Location: kernel/signal.c:436
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810a49c0-ffffffff810a49f0: __sigqueue_free.part.38 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aec60)
Location: kernel/signal.c:446
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810a9690-ffffffff810a96c2: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810b5277)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810afc20-ffffffff810afc56: __sigqueue_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810baa68)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
**Symbols:**

```
ffffffff810b7790-ffffffff810b77c8: __sigqueue_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810b5d28)
Location: kernel/signal.c:452
Inline: True
Inline callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
Direct callers:
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:dequeue_synchronous_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
**Symbols:**

```
ffffffff810b2a20-ffffffff810b2a58: __sigqueue_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810ba95b)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
**Symbols:**

```
ffffffff810b4060-ffffffff810b4098: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810cd20a)
Location: kernel/signal.c:450
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:flush_sigqueue
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
In kernel/signal.c (ffffffff810e51dd)
Location: kernel/signal.c:450
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:flush_sigqueue
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
In kernel/signal.c (ffffffff811058a2)
Location: kernel/signal.c:450
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:flush_sigqueue
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
In kernel/signal.c (ffffffff81111b44)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:flush_sigqueue
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
In kernel/signal.c (ffffffff8111b4e4)
Location: kernel/signal.c:442
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:flush_sigqueue
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
In kernel/signal.c (ffff8000101114f8)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffff80001010aeb8-ffff80001010af44: __sigqueue_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (c0368b68)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
c0363ec4-c0363f30: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (c000000000158ec8)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
c0000000001522c0-c000000000152364: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffe0000d0e1c)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:collect_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffe0000cd6c8-ffffffe0000cd718: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810af5e7)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810a9f90-ffffffff810a9fc6: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff8109df2b)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810989a0-ffffffff810989d6: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810aeb47)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810a94f0-ffffffff810a9526: __sigqueue_free.part.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810b6df6)
Location: kernel/signal.c:451
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:sigqueue_free
  - kernel/signal.c:flush_sigqueue_mask
  - kernel/signal.c:__dequeue_signal
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
**Symbols:**

```
ffffffff810b1810-ffffffff810b1846: __sigqueue_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
