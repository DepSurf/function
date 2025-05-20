# Function: <code>__irq_get_irqchip_state</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110aa84)
Location: kernel/irq/manage.c:2626
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff8110d6b0-ffffffff8110d6e4: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81116e54)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff81119aa0-ffffffff81119ad4: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81125370)
Location: kernel/irq/manage.c:2657
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff81125370-ffffffff811253b1: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811211d0)
Location: kernel/irq/manage.c:2727
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff811211d0-ffffffff81121211: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811214b0)
Location: kernel/irq/manage.c:2734
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff811214b0-ffffffff811214f1: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141a30)
Location: kernel/irq/manage.c:2763
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff81141a30-ffffffff81141a71: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811654f0)
Location: kernel/irq/manage.c:2797
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff811654f0-ffffffff8116554f: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811993f0)
Location: kernel/irq/manage.c:2789
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff811993f0-ffffffff8119944f: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a868e)
Location: kernel/irq/manage.c:2795
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
Direct callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff811ab0d0-ffffffff811ab12f: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b810e)
Location: kernel/irq/manage.c:2792
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
Direct callers:
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff811bad10-ffffffff811bad6f: __irq_get_irqchip_state (STB_GLOBAL)
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
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010178dd4)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffff80001017c868-ffff80001017c8dc: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca76c)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
c03cd750-c03cd79c: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d30c4)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
c0000000001d7550-c0000000001d75b8: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe00011382a)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffe000115de8-ffffffe000115e3a: __irq_get_irqchip_state (STB_GLOBAL)
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
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f434)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff81112080-ffffffff811120b4: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81100174)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff81102db0-ffffffff81102de4: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d324)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff8110ff70-ffffffff8110ffa4: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __irq_get_irqchip_state(struct irq_data *data, enum irqchip_irq_state which, bool *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118884)
Location: kernel/irq/manage.c:2618
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_get_irqchip_state
  - kernel/irq/manage.c:__synchronize_hardirq
```
**Symbols:**

```
ffffffff8111b4e0-ffffffff8111b514: __irq_get_irqchip_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
