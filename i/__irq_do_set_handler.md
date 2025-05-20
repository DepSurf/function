# Function: <code>__irq_do_set_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810de570)
Location: kernel/irq/chip.c:734
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_set_handler
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff810de570-ffffffff810de6db: __irq_do_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e3eb0)
Location: kernel/irq/chip.c:777
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff810e3eb0-ffffffff810e403d: __irq_do_set_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea410)
Location: kernel/irq/chip.c:786
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff810ea410-ffffffff810ea58d: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9b10)
Location: kernel/irq/chip.c:891
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff810e9b10-ffffffff810e9cad: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f2060)
Location: kernel/irq/chip.c:914
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff810f2060-ffffffff810f21fe: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa4b0)
Location: kernel/irq/chip.c:912
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff810fa4b0-ffffffff810fa642: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105c70)
Location: kernel/irq/chip.c:912
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff81105c70-ffffffff81105e02: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (0)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff8110f130-ffffffff8110f2ab: __irq_do_set_handler (STB_LOCAL)
ffffffff8110fad9-ffffffff8110faec: __irq_do_set_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b3f0)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff8111b3f0-ffffffff8111b568: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127590)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff81127590-ffffffff81127722: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123190)
Location: kernel/irq/chip.c:973
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff81123190-ffffffff81123322: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811234f0)
Location: kernel/irq/chip.c:976
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff811234f0-ffffffff81123682: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143ac0)
Location: kernel/irq/chip.c:976
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff81143ac0-ffffffff81143c52: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167f20)
Location: kernel/irq/chip.c:971
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff81167f20-ffffffff81168133: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c3e0)
Location: kernel/irq/chip.c:973
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff8119c3e0-ffffffff8119c5f3: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae230)
Location: kernel/irq/chip.c:988
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff811ae230-ffffffff811ae480: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bde30)
Location: kernel/irq/chip.c:985
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chip_and_handler_name
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
```
**Symbols:**

```
ffffffff811bde30-ffffffff811be080: __irq_do_set_handler (STB_LOCAL)
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
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f3e0)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffff80001017f3e0-ffff80001017f594: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf610)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
c03cf610-c03cf7d0: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9d70)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
c0000000001d9d70-c0000000001d9ffc: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe00011792e)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffe00011792e-ffffffe000117a5e: __irq_do_set_handler (STB_LOCAL)
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
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811139d0)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff811139d0-ffffffff81113b48: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811046e0)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff811046e0-ffffffff81104858: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811118c0)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff811118c0-ffffffff81111a38: __irq_do_set_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc *desc, irq_flow_handler_t handle, int is_chained, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111ce80)
Location: kernel/irq/chip.c:984
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_set_chained_handler_and_data
  - kernel/irq/chip.c:__irq_set_handler
```
**Symbols:**

```
ffffffff8111ce80-ffffffff8111cff8: __irq_do_set_handler (STB_LOCAL)
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
