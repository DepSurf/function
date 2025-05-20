# Function: <code>fast_mix</code>

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
In drivers/char/random.c (ffffffff81515364)
Location: drivers/char/random.c:569
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff815674f7)
Location: drivers/char/random.c:595
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff81593c27)
Location: drivers/char/random.c:595
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff815a79a5)
Location: drivers/char/random.c:587
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff8160e2a5)
Location: drivers/char/random.c:586
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff81647d7e)
Location: drivers/char/random.c:598
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff8166621e)
Location: drivers/char/random.c:597
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff8169bf10)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff816bec40)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81773907)
Location: drivers/char/random.c:614
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff8178e8c0)
Location: drivers/char/random.c:614
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff8177153b)
Location: drivers/char/random.c:613
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff817f70eb)
Location: drivers/char/random.c:614
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fast_mix(long unsigned int *s, long unsigned int v1, long unsigned int v2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81933a80)
Location: drivers/char/random.c:928
Inline: False
Direct callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff81933a80-ffffffff81933b32: fast_mix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fast_mix(long unsigned int *s, long unsigned int v1, long unsigned int v2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a928a0)
Location: drivers/char/random.c:1019
Inline: False
Direct callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff81a928a0-ffffffff81a92952: fast_mix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fast_mix(long unsigned int *s, long unsigned int v1, long unsigned int v2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81ade120)
Location: drivers/char/random.c:1019
Inline: False
Direct callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff81ade120-ffffffff81ade1d2: fast_mix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fast_mix(long unsigned int *s, long unsigned int v1, long unsigned int v2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b31540)
Location: drivers/char/random.c:1019
Inline: False
Direct callers:
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_interrupt_randomness
```
**Symbols:**

```
ffffffff81b31540-ffffffff81b315f2: fast_mix (STB_LOCAL)
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
In drivers/char/random.c (ffff8000108b06fc)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (c09ab0a4)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (c000000000947478)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffe00056333e)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff816846b0)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff81662330)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff816b2a80)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
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
In drivers/char/random.c (ffffffff816ccfd0)
Location: drivers/char/random.c:665
Inline: True
Inline callers:
  - drivers/char/random.c:add_interrupt_randomness
```
</details>
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
