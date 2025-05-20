# Function: <code>irq_wait_for_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810dd430)
Location: kernel/irq/spurious.c:38
Inline: False
```
**Symbols:**

```
ffffffff810dd430-ffffffff810dd4ee: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810e2bf0)
Location: kernel/irq/spurious.c:38
Inline: False
```
**Symbols:**

```
ffffffff810e2bf0-ffffffff810e2caa: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810e94f0)
Location: kernel/irq/spurious.c:38
Inline: False
```
**Symbols:**

```
ffffffff810e94f0-ffffffff810e95a7: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810e89c0)
Location: kernel/irq/spurious.c:38
Inline: False
```
**Symbols:**

```
ffffffff810e89c0-ffffffff810e8a61: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810f0d90)
Location: kernel/irq/spurious.c:39
Inline: False
```
**Symbols:**

```
ffffffff810f0d90-ffffffff810f0e3c: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810f9110)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff810f9110-ffffffff810f91bc: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff811048b0)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff811048b0-ffffffff81104967: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff8110dad0)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff8110dad0-ffffffff8110db77: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81119d90)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff81119d90-ffffffff81119e37: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81125d60)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81125d60-ffffffff81125e07: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81121a70)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81121a70-ffffffff81121b17: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81121cb0)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81121cb0-ffffffff81121d57: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81cad96e-ffffffff81cad983: irq_wait_for_poll.cold (STB_LOCAL)
ffffffff81142250-ffffffff81142309: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81e5de51-ffffffff81e5de66: irq_wait_for_poll.cold (STB_LOCAL)
ffffffff81165d90-ffffffff81165e5e: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff820599f1-ffffffff82059a06: irq_wait_for_poll.cold (STB_LOCAL)
ffffffff81199e70-ffffffff81199f3e: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff820d8114-ffffffff820d8131: irq_wait_for_poll.cold (STB_LOCAL)
ffffffff811abaa0-ffffffff811abb62: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:36
Inline: False
Direct callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_untracked_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff821b3395-ffffffff821b33b2: irq_wait_for_poll.cold (STB_LOCAL)
ffffffff811bb6a0-ffffffff811bb762: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffff80001017ce70)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffff80001017ce70-ffff80001017cf88: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (c03cd978)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
c03cd978-c03cdab0: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (c0000000001d78e0)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
c0000000001d78e0-c0000000001d7a60: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffe000115fe2)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffe000115fe2-ffffffe0001160d6: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81112370)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff81112370-ffffffff81112417: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81103090)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff81103090-ffffffff81103137: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81110260)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff81110260-ffffffff81110307: irq_wait_for_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool irq_wait_for_poll(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff8111b7e0)
Location: kernel/irq/spurious.c:36
Inline: False
```
**Symbols:**

```
ffffffff8111b7e0-ffffffff8111b885: irq_wait_for_poll (STB_GLOBAL)
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
