# Function: <code>irq_wait_for_interrupt</code>

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
In kernel/irq/manage.c (ffffffff810dbd5f)
Location: kernel/irq/manage.c:745
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff810e141e)
Location: kernel/irq/manage.c:759
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff810e77ae)
Location: kernel/irq/manage.c:759
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff810e71fe)
Location: kernel/irq/manage.c:736
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff810ef4f3)
Location: kernel/irq/manage.c:764
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff810f78d3)
Location: kernel/irq/manage.c:797
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff811031d7)
Location: kernel/irq/manage.c:800
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff8110b857)
Location: kernel/irq/manage.c:867
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff81117b57)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_wait_for_interrupt(struct irqaction *action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81122c40)
Location: kernel/irq/manage.c:943
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
```
**Symbols:**

```
ffffffff81122c40-ffffffff81122cc2: irq_wait_for_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_wait_for_interrupt(struct irqaction *action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111ea70)
Location: kernel/irq/manage.c:1013
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
```
**Symbols:**

```
ffffffff8111ea70-ffffffff8111eaf2: irq_wait_for_interrupt (STB_LOCAL)
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
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1013
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1037
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1052
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1044
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1050
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1052
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffff800010179910)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (c03cb5b8)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (c0000000001d40f8)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffe000114484)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff81110137)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff81100e67)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff8110e027)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
In kernel/irq/manage.c (ffffffff81119567)
Location: kernel/irq/manage.c:860
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
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
