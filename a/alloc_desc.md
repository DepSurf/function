# Function: <code>alloc_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810da0d0)
Location: kernel/irq/irqdesc.c:144
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810da0d0-ffffffff810da2c8: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810df5c0)
Location: kernel/irq/irqdesc.c:166
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810df5c0-ffffffff810df7cd: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5d00)
Location: kernel/irq/irqdesc.c:342
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810e5d00-ffffffff810e5efe: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810e5320)
Location: kernel/irq/irqdesc.c:357
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810e5320-ffffffff810e554c: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810ed580)
Location: kernel/irq/irqdesc.c:355
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810ed580-ffffffff810ed79b: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810f5950)
Location: kernel/irq/irqdesc.c:372
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810f5950-ffffffff810f5b6b: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811010e0)
Location: kernel/irq/irqdesc.c:372
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff811010e0-ffffffff811012fb: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811098e0)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff811098e0-ffffffff81109af8: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81115cb0)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff81115cb0-ffffffff81115ec8: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811217b0)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff811217b0-ffffffff811218ec: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111d8e0)
Location: kernel/irq/irqdesc.c:389
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff8111d8e0-ffffffff8111da1c: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111daa0)
Location: kernel/irq/irqdesc.c:389
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff8111daa0-ffffffff8111dcbb: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113deb0)
Location: kernel/irq/irqdesc.c:389
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff8113deb0-ffffffff8113e0f9: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811614b0)
Location: kernel/irq/irqdesc.c:389
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff811614b0-ffffffff81161722: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81194b30)
Location: kernel/irq/irqdesc.c:392
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff81194b30-ffffffff81194dab: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:412
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff811a62b0-ffffffff811a6588: alloc_desc (STB_LOCAL)
ffffffff820d7f58-ffffffff820d7f73: alloc_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:412
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
```
**Symbols:**

```
ffffffff811b5da0-ffffffff811b60a7: alloc_desc (STB_LOCAL)
ffffffff821b31d9-ffffffff821b31f4: alloc_desc.cold (STB_LOCAL)
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
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010177458)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffff800010177458-ffff800010177604: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c03c9364)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
c03c9364-c03c94ec: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d0ff0)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
c0000000001d0ff0-c0000000001d1224: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe000112496)
Location: kernel/irq/irqdesc.c:387
Inline: True
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffe000112496-ffffffe000112642: alloc_desc.isra.0 (STB_LOCAL)
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
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110e290)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff8110e290-ffffffff8110e4a8: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff810feff0)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff810feff0-ffffffff810ff208: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8110c180)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff8110c180-ffffffff8110c398: alloc_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_desc *alloc_desc(int irq, int node, unsigned int flags, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811178b0)
Location: kernel/irq/irqdesc.c:387
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:early_irq_init
```
**Symbols:**

```
ffffffff811178b0-ffffffff81117ac8: alloc_desc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param added. </b>
<code>const struct cpumask *affinity</code>
</li>
<li>
<b>Param reordered. </b>
<code>irq, node, owner</code> ➡️ <code>irq, node, flags, affinity, owner</code>
</li>
</ul>
</details>
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
