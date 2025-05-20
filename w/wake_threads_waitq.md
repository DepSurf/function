# Function: <code>wake_threads_waitq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810db460)
Location: kernel/irq/manage.c:893
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread
```
**Symbols:**

```
ffffffff810db460-ffffffff810db48d: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0b00)
Location: kernel/irq/manage.c:907
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810e0b00-ffffffff810e0b2d: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7510)
Location: kernel/irq/manage.c:907
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810e7510-ffffffff810e753d: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6af0)
Location: kernel/irq/manage.c:884
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810e6af0-ffffffff810e6b1e: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810eedb0)
Location: kernel/irq/manage.c:912
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810eedb0-ffffffff810eedde: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f71a0)
Location: kernel/irq/manage.c:949
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff810f71a0-ffffffff810f71ce: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102910)
Location: kernel/irq/manage.c:965
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff81102910-ffffffff8110293e: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110b2d0)
Location: kernel/irq/manage.c:1032
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff8110b2d0-ffffffff8110b2fd: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81117400)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff81117400-ffffffff8111742d: wake_threads_waitq (STB_LOCAL)
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
In kernel/irq/manage.c (ffffffff811235da)
Location: kernel/irq/manage.c:1108
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
In kernel/irq/manage.c (ffffffff8111f42a)
Location: kernel/irq/manage.c:1182
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
In kernel/irq/manage.c (ffffffff8111f583)
Location: kernel/irq/manage.c:1182
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
In kernel/irq/manage.c (ffffffff8113f9ef)
Location: kernel/irq/manage.c:1206
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
In kernel/irq/manage.c (ffffffff81163390)
Location: kernel/irq/manage.c:1221
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
In kernel/irq/manage.c (ffffffff81196fd0)
Location: kernel/irq/manage.c:1213
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
In kernel/irq/manage.c (ffffffff811a8ae0)
Location: kernel/irq/manage.c:1219
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b8640)
Location: kernel/irq/manage.c:1221
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
Direct callers:
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff811ba4b0-ffffffff811ba4f9: wake_threads_waitq (STB_GLOBAL)
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
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010179340)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffff800010179340-ffff8000101793b4: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cb270)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
c03cb270-c03cb2c4: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d3cc0)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
c0000000001d3cc0-c0000000001d3d2c: wake_threads_waitq (STB_LOCAL)
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
In kernel/irq/manage.c (ffffffe000114522)
Location: kernel/irq/manage.c:1025
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
  - kernel/irq/manage.c:irq_thread_dtor
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
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f9e0)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff8110f9e0-ffffffff8110fa0d: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81100720)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff81100720-ffffffff8110074d: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d8d0)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff8110d8d0-ffffffff8110d8fd: wake_threads_waitq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wake_threads_waitq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118ff0)
Location: kernel/irq/manage.c:1025
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/irq/manage.c:irq_thread_dtor
```
**Symbols:**

```
ffffffff81118ff0-ffffffff8111901d: wake_threads_waitq (STB_LOCAL)
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
