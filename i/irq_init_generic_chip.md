# Function: <code>irq_init_generic_chip</code>

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
In kernel/irq/generic-chip.c (ffffffff810df91b)
Location: kernel/irq/generic-chip.c:205
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
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
In kernel/irq/generic-chip.c (ffffffff810e52a4)
Location: kernel/irq/generic-chip.c:205
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
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
In kernel/irq/generic-chip.c (ffffffff810ebbb4)
Location: kernel/irq/generic-chip.c:205
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810eb449)
Location: kernel/irq/generic-chip.c:204
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff810eb810-ffffffff810eb839: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810f39b6)
Location: kernel/irq/generic-chip.c:213
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff810f3d80-ffffffff810f3da9: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810fbb91)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff810fc170-ffffffff810fc199: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81107361)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81107940-ffffffff81107969: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81110933)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81110f00-ffffffff81110f29: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8111cb93)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff8111d160-ffffffff8111d189: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81128c95)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81129490-ffffffff811294b9: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81124595)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81124d60-ffffffff81124d89: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811248e5)
Location: kernel/irq/generic-chip.c:215
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff811250c0-ffffffff811250e9: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81144f5f)
Location: kernel/irq/generic-chip.c:215
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81145760-ffffffff81145789: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8116923d)
Location: kernel/irq/generic-chip.c:218
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81169880-ffffffff811698bb: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8119dafd)
Location: kernel/irq/generic-chip.c:218
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff8119e1f0-ffffffff8119e22b: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811af9b5)
Location: kernel/irq/generic-chip.c:218
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff811b0090-ffffffff811b00cb: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff811bf528)
Location: kernel/irq/generic-chip.c:218
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff811bfdc0-ffffffff811bfe42: irq_init_generic_chip (STB_GLOBAL)
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
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffff800010181050)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffff800010181f98-ffff800010181ff8: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (c03d11e4)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
c03d17f8-c03d1830: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (c0000000001dc72c)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
c0000000001dd3b0-c0000000001dd3d8: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffe000119364)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffe000119d52-ffffffe000119da8: irq_init_generic_chip (STB_GLOBAL)
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
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81115173)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81115740-ffffffff81115769: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81105e83)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81106450-ffffffff81106479: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81113063)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff81113630-ffffffff81113659: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_init_generic_chip(struct irq_chip_generic *gc, const char *name, int num_ct, unsigned int irq_base, void *reg_base, irq_flow_handler_t handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff8111e8a3)
Location: kernel/irq/generic-chip.c:214
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:__irq_alloc_domain_generic_chips
  - kernel/irq/generic-chip.c:irq_alloc_generic_chip
Direct callers:
  - kernel/irq/devres.c:devm_irq_alloc_generic_chip
```
**Symbols:**

```
ffffffff8111ec90-ffffffff8111ecb9: irq_init_generic_chip (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
