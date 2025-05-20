# Function: <code>misrouted_irq</code>

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
In kernel/irq/spurious.c (ffffffff810dd579)
Location: kernel/irq/spurious.c:119
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff810e2d39)
Location: kernel/irq/spurious.c:119
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff810e9630)
Location: kernel/irq/spurious.c:119
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff810e8acc)
Location: kernel/irq/spurious.c:119
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff810f0e9c)
Location: kernel/irq/spurious.c:120
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff810f923f)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff811049ef)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff8110dc01)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff81119ec1)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int misrouted_irq(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81125cc0)
Location: kernel/irq/spurious.c:118
Inline: False
Direct callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
```
**Symbols:**

```
ffffffff81125cc0-ffffffff81125d59: misrouted_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int misrouted_irq(int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff811219d0)
Location: kernel/irq/spurious.c:118
Inline: False
Direct callers:
  - kernel/irq/spurious.c:note_interrupt
  - kernel/irq/spurious.c:note_interrupt
```
**Symbols:**

```
ffffffff811219d0-ffffffff81121a69: misrouted_irq (STB_LOCAL)
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
In kernel/irq/spurious.c (ffffffff81121de1)
Location: kernel/irq/spurious.c:118
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff81142391)
Location: kernel/irq/spurious.c:118
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff81165eea)
Location: kernel/irq/spurious.c:118
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff81199fda)
Location: kernel/irq/spurious.c:118
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff811abbfe)
Location: kernel/irq/spurious.c:118
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff811bb7fe)
Location: kernel/irq/spurious.c:118
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffff80001017d078)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (c03cdb34)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (c0000000001d7b00)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffe0001161c8)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff811124a1)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff811031c1)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff81110391)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
In kernel/irq/spurious.c (ffffffff8111b911)
Location: kernel/irq/spurious.c:117
Inline: True
Inline callers:
  - kernel/irq/spurious.c:note_interrupt
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
