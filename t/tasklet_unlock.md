# Function: <code>tasklet_unlock</code>

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
In kernel/softirq.c (ffffffff810851e8)
Location: include/linux/interrupt.h:515
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:tasklet_action
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
In kernel/softirq.c (ffffffff810883ee)
Location: include/linux/interrupt.h:534
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:tasklet_action
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
In kernel/softirq.c (ffffffff8108d41e)
Location: include/linux/interrupt.h:554
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:tasklet_action
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
In kernel/softirq.c (ffffffff8108a44e)
Location: include/linux/interrupt.h:563
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:tasklet_action
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
In kernel/softirq.c (ffffffff81091514)
Location: include/linux/interrupt.h:565
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_hi_action
  - kernel/softirq.c:tasklet_action
  - kernel/softirq.c:tasklet_action
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
In kernel/softirq.c (ffffffff81094f9f)
Location: include/linux/interrupt.h:570
Inline: True
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
In kernel/softirq.c (ffffffff8109cdcf)
Location: include/linux/interrupt.h:586
Inline: True
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
In kernel/softirq.c (ffffffff810a1550)
Location: include/linux/interrupt.h:615
Inline: True
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
In kernel/softirq.c (ffffffff810a7b10)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (ffffffff810af5bb)
Location: include/linux/interrupt.h:634
Inline: True
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
In kernel/softirq.c (ffffffff810aad58)
Location: include/linux/interrupt.h:672
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab590)
Location: kernel/softirq.c:877
Inline: True
```
**Symbols:**

```
ffffffff810ab590-ffffffff810ab5ac: tasklet_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bd0b0)
Location: kernel/softirq.c:876
Inline: True
```
**Symbols:**

```
ffffffff810bd0b0-ffffffff810bd0cc: tasklet_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d41a0)
Location: kernel/softirq.c:890
Inline: True
```
**Symbols:**

```
ffffffff810d41a0-ffffffff810d41c4: tasklet_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f30d0)
Location: kernel/softirq.c:890
Inline: True
```
**Symbols:**

```
ffffffff810f30d0-ffffffff810f30f4: tasklet_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ff410)
Location: kernel/softirq.c:877
Inline: True
```
**Symbols:**

```
ffffffff810ff410-ffffffff810ff434: tasklet_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81108ac0)
Location: kernel/softirq.c:877
Inline: True
```
**Symbols:**

```
ffffffff81108ac0-ffffffff81108ae4: tasklet_unlock (STB_GLOBAL)
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
In kernel/softirq.c (ffff8000100ff3bc)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (c035c098)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (c000000000146784)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (ffffffe0000c7256)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (ffffffff810a1430)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (ffffffff8108fee4)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (ffffffff810a13e0)
Location: include/linux/interrupt.h:620
Inline: True
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
In kernel/softirq.c (ffffffff810a9360)
Location: include/linux/interrupt.h:620
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
