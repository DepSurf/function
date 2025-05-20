# Function: <code>mfd_add_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8158a7e0)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_devices
  - drivers/mfd/mfd-core.c:mfd_clone_cell
```
**Symbols:**

```
ffffffff8158a7e0-ffffffff8158adab: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff815df9a0)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff815df9a0-ffffffff815dff47: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff8160c640)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff8160c640-ffffffff8160cbe7: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81620730)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff81620730-ffffffff81620cf0: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81688f80)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff81688f80-ffffffff8168950b: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816c50d0)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff816c50d0-ffffffff816c5638: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816e64c0)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff816e64c0-ffffffff816e6a2a: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff8171fc70-ffffffff817201f1: mfd_add_device (STB_LOCAL)
ffffffff817204ae-ffffffff817204d7: mfd_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81743f40)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff81743f40-ffffffff817444cb: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81801c80)
Location: drivers/mfd/mfd-core.c:110
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff81801c80-ffffffff81801f75: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81812a40)
Location: drivers/mfd/mfd-core.c:165
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff81812a40-ffffffff81812da9: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff817f7150)
Location: drivers/mfd/mfd-core.c:153
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff817f7150-ffffffff817f74ca: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: drivers/mfd/mfd-core.c:153
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff81880460-ffffffff818807f4: mfd_add_device (STB_LOCAL)
ffffffff81d08cba-ffffffff81d08cef: mfd_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: drivers/mfd/mfd-core.c:153
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff819c8b20-ffffffff819c8edf: mfd_add_device (STB_LOCAL)
ffffffff81ed10db-ffffffff81ed1118: mfd_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: drivers/mfd/mfd-core.c:170
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff81b3fe40-ffffffff81b40200: mfd_add_device (STB_LOCAL)
ffffffff8209a261-ffffffff8209a29e: mfd_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff81b931d0-ffffffff81b9357a: mfd_add_device (STB_LOCAL)
ffffffff8211b305-ffffffff8211b33a: mfd_add_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: drivers/mfd/mfd-core.c:140
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:devm_mfd_add_devices
```
**Symbols:**

```
ffffffff81be7170-ffffffff81be751a: mfd_add_device (STB_LOCAL)
ffffffff821f918c-ffffffff821f91c1: mfd_add_device.cold (STB_LOCAL)
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
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffff800010940010)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffff800010940010-ffff8000109404b0: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0a29814)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
c0a29814-c0a29b88: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (c0000000009e8b40)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
c0000000009e8b40-c0000000009e8f80: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffe0005b3c32)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffe0005b3c32-ffffffe0005b3eb0: mfd_add_device (STB_LOCAL)
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
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81701fe0)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff81701fe0-ffffffff8170256b: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff816d5df0)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff816d5df0-ffffffff816d637b: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81737400)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff81737400-ffffffff8173798b: mfd_add_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mfd_add_device(struct device *parent, int id, const struct mfd_cell *cell, atomic_t *usage_count, struct resource *mem_base, int irq_base, struct irq_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (ffffffff81752840)
Location: drivers/mfd/mfd-core.c:136
Inline: False
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_clone_cell
  - drivers/mfd/mfd-core.c:mfd_add_devices
```
**Symbols:**

```
ffffffff81752840-ffffffff81752dcb: mfd_add_device (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>atomic_t *usage_count</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, id, cell, usage_count, mem_base, irq_base, domain</code> ➡️ <code>parent, id, cell, mem_base, irq_base, domain</code>
</li>
</ul>
</details>
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
