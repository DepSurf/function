# Function: <code>mask_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ddc81)
Location: kernel/irq/chip.c:293
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff810de340-ffffffff810de36e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e391e)
Location: kernel/irq/chip.c:293
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff810e3c90-ffffffff810e3cbe: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea17f)
Location: kernel/irq/chip.c:292
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff810ea7c0-ffffffff810ea7ee: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9c5f)
Location: kernel/irq/chip.c:391
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff810e92f0-ffffffff810e931f: mask_irq.part.30 (STB_LOCAL)
ffffffff810e9eb0-ffffffff810e9ecf: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f21ad)
Location: kernel/irq/chip.c:414
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff810f1750-ffffffff810f1782: mask_irq.part.31 (STB_LOCAL)
ffffffff810f2400-ffffffff810f241f: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa5f1)
Location: kernel/irq/chip.c:412
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff810f9a40-ffffffff810f9a71: mask_irq.part.32 (STB_LOCAL)
ffffffff810fa850-ffffffff810fa86e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105db1)
Location: kernel/irq/chip.c:412
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81105200-ffffffff81105231: mask_irq.part.34 (STB_LOCAL)
ffffffff81106010-ffffffff8110602e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110f254)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8110e4e0-ffffffff8110e511: mask_irq.part.0 (STB_LOCAL)
ffffffff8110f4b0-ffffffff8110f4ce: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b524)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8111a7a0-ffffffff8111a7d1: mask_irq.part.0 (STB_LOCAL)
ffffffff8111b770-ffffffff8111b78e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811276c4)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81127a20-ffffffff81127a61: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811232c4)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81123620-ffffffff81123661: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123624)
Location: kernel/irq/chip.c:421
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81123980-ffffffff811239c1: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143bf4)
Location: kernel/irq/chip.c:421
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81143f50-ffffffff81143f91: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811680da)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81167a10-ffffffff81167a61: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c59a)
Location: kernel/irq/chip.c:420
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8119be30-ffffffff8119be81: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae427)
Location: kernel/irq/chip.c:421
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff811adc90-ffffffff811adce1: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811be027)
Location: kernel/irq/chip.c:421
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
  - kernel/irq/chip.c:irq_disable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff811bd890-ffffffff811bd8e1: mask_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffff80001017ed60)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffff80001017dec0-ffff80001017df08: mask_irq.part.0 (STB_LOCAL)
ffff80001017f860-ffff80001017f898: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (c03cf78c)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
c03ce7b4-c03ce7f8: mask_irq.part.0 (STB_LOCAL)
c03cf9e0-c03cfa0c: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9e20)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
c0000000001d8a10-c0000000001d8a7c: mask_irq.part.0 (STB_LOCAL)
c0000000001da360-c0000000001da384: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffe000117a36)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
```
**Symbols:**

```
ffffffe0001169f2-ffffffe000116a2a: mask_irq.part.0 (STB_LOCAL)
ffffffe000117c68-ffffffe000117c9e: mask_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113b04)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81112d80-ffffffff81112db1: mask_irq.part.0 (STB_LOCAL)
ffffffff81113d50-ffffffff81113d6e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104814)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81103aa0-ffffffff81103ad1: mask_irq.part.0 (STB_LOCAL)
ffffffff81104a60-ffffffff81104a7e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff811119f4)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff81110c70-ffffffff81110ca1: mask_irq.part.0 (STB_LOCAL)
ffffffff81111c40-ffffffff81111c5e: mask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111cfb4)
Location: kernel/irq/chip.c:418
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/pm.c:suspend_device_irqs
```
**Symbols:**

```
ffffffff8111c440-ffffffff8111c471: mask_irq.part.0 (STB_LOCAL)
ffffffff8111d200-ffffffff8111d21e: mask_irq (STB_GLOBAL)
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
