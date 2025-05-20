# Function: <code>klp_send_signals</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klp_send_signals();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8110c401)
Location: kernel/livepatch/transition.c:583
Inline: False
```
**Symbols:**

```
ffffffff8110c401-ffffffff8110c4ee: klp_send_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_send_signals();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81117bf1)
Location: kernel/livepatch/transition.c:576
Inline: False
```
**Symbols:**

```
ffffffff81117bf1-ffffffff81117cde: klp_send_signals (STB_GLOBAL)
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
In kernel/livepatch/transition.c (ffffffff81121a1d)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff8112e03d)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void klp_send_signals();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:343
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8113c450-ffffffff8113c550: klp_send_signals (STB_LOCAL)
ffffffff8113ceb8-ffffffff8113cec9: klp_send_signals.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void klp_send_signals();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/transition.c (0)
Location: kernel/livepatch/transition.c:343
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81136b60-ffffffff81136c60: klp_send_signals (STB_LOCAL)
ffffffff81be3463-ffffffff81be3474: klp_send_signals.cold (STB_LOCAL)
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
In kernel/livepatch/transition.c (ffffffff81137df7)
Location: kernel/livepatch/transition.c:344
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff8115ab47)
Location: kernel/livepatch/transition.c:344
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff8118440a)
Location: kernel/livepatch/transition.c:341
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff811bf6b4)
Location: kernel/livepatch/transition.c:341
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff811d2194)
Location: kernel/livepatch/transition.c:408
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff811e6e14)
Location: kernel/livepatch/transition.c:408
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f3158)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/livepatch/transition.c (ffffffff8112661d)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff8111907d)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff8112450d)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
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
In kernel/livepatch/transition.c (ffffffff81130b6c)
Location: kernel/livepatch/transition.c:343
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
