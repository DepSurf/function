# Function: <code>irq_pm_check_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff810e2900)
Location: kernel/irq/pm.c:17
Inline: False
```
**Symbols:**

```
ffffffff810e2900-ffffffff810e294c: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff810e8390)
Location: kernel/irq/pm.c:17
Inline: False
```
**Symbols:**

```
ffffffff810e8390-ffffffff810e83dc: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff810eedc0)
Location: kernel/irq/pm.c:17
Inline: False
```
**Symbols:**

```
ffffffff810eedc0-ffffffff810eee06: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff810eec50)
Location: kernel/irq/pm.c:17
Inline: False
```
**Symbols:**

```
ffffffff810eec50-ffffffff810eec99: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff810f7700)
Location: kernel/irq/pm.c:17
Inline: False
```
**Symbols:**

```
ffffffff810f7700-ffffffff810f7749: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff810ffa60)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff810ffa60-ffffffff810ffaa9: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff8110b240)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff8110b240-ffffffff8110b289: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81114920)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff81114920-ffffffff8111496f: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81120a80)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff81120a80-ffffffff81120acf: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff8112d040)
Location: kernel/irq/pm.c:16
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
ffffffff8112d040-ffffffff8112d092: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81128aa0)
Location: kernel/irq/pm.c:16
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
ffffffff81128aa0-ffffffff81128af2: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81128d30)
Location: kernel/irq/pm.c:16
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
ffffffff81128d30-ffffffff81128d7a: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81149310)
Location: kernel/irq/pm.c:16
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
ffffffff81149310-ffffffff8114935a: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff8116de80)
Location: kernel/irq/pm.c:16
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
ffffffff8116de80-ffffffff8116dede: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff811a2f80)
Location: kernel/irq/pm.c:16
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
ffffffff811a2f80-ffffffff811a2fde: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff811b4e80)
Location: kernel/irq/pm.c:16
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
ffffffff811b4e80-ffffffff811b4ede: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff811c4d00)
Location: kernel/irq/pm.c:16
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
ffffffff811c4d00-ffffffff811c4d5e: irq_pm_check_wakeup (STB_GLOBAL)
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
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffff800010186a38)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffff800010186a38-ffff800010186aa8: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (c03d5668)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
c03d5668-c03d56c8: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (c0000000001e1250)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
c0000000001e1250-c0000000001e12e0: irq_pm_check_wakeup (STB_GLOBAL)
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
In kernel/irq/chip.c (0)
Location: kernel/irq/internals.h:277
Inline: True
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
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81119060)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff81119060-ffffffff811190af: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff8110a0d0)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff8110a0d0-ffffffff8110a11f: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81116f50)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff81116f50-ffffffff81116f9f: irq_pm_check_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool irq_pm_check_wakeup(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff811225e0)
Location: kernel/irq/pm.c:16
Inline: False
```
**Symbols:**

```
ffffffff811225e0-ffffffff8112262f: irq_pm_check_wakeup (STB_GLOBAL)
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
