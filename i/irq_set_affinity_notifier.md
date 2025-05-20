# Function: <code>irq_set_affinity_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810db490)
Location: kernel/irq/manage.c:304
Inline: False
Direct callers:
  - lib/cpu_rmap.c:free_irq_cpu_rmap
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff810db490-ffffffff810db569: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0b30)
Location: kernel/irq/manage.c:317
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
**Symbols:**

```
ffffffff810e0b30-ffffffff810e0bfe: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7540)
Location: kernel/irq/manage.c:317
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:free_irq_cpu_rmap
```
**Symbols:**

```
ffffffff810e7540-ffffffff810e760e: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6130)
Location: kernel/irq/manage.c:291
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff810e6130-ffffffff810e61dc: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ee3c0)
Location: kernel/irq/manage.c:308
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff810ee3c0-ffffffff810ee479: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f67b0)
Location: kernel/irq/manage.c:341
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff810f67b0-ffffffff810f686b: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81101f20)
Location: kernel/irq/manage.c:341
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff81101f20-ffffffff81101fdb: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110b1c0)
Location: kernel/irq/manage.c:368
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8110b1c0-ffffffff8110b290: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81117be0)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81117be0-ffffffff81117cd2: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81122ee0)
Location: kernel/irq/manage.c:448
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81122ee0-ffffffff81123007: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111eed0)
Location: kernel/irq/manage.c:518
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff8111eed0-ffffffff8111eff7: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111f150)
Location: kernel/irq/manage.c:518
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff8111f150-ffffffff8111f277: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113f5e0)
Location: kernel/irq/manage.c:542
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff8113f5e0-ffffffff8113f707: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163070)
Location: kernel/irq/manage.c:557
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff81163070-ffffffff81163198: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81196c80)
Location: kernel/irq/manage.c:549
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffff81196c80-ffffffff81196da8: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a8730)
Location: kernel/irq/manage.c:552
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_remove
```
**Symbols:**

```
ffffffff811a8730-ffffffff811a885c: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b81b0)
Location: kernel/irq/manage.c:554
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - lib/cpu_rmap.c:irq_cpu_rmap_remove
```
**Symbols:**

```
ffffffff811b81b0-ffffffff811b82dc: irq_set_affinity_notifier (STB_GLOBAL)
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
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff800010179e30)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffff800010179e30-ffff800010179f90: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03ca7ec)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
c03ca7ec-c03ca8ec: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d3160)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
c0000000001d3160-c0000000001d3328: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000113866)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
**Symbols:**

```
ffffffe000113866-ffffffe00011394e: irq_set_affinity_notifier (STB_GLOBAL)
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
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811101c0)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff811101c0-ffffffff811102b2: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81100ef0)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff81100ef0-ffffffff81100fe2: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110e0b0)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff8110e0b0-ffffffff8110e1a2: irq_set_affinity_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_set_affinity_notifier(unsigned int irq, struct irq_affinity_notify *notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811195f0)
Location: kernel/irq/manage.c:372
Inline: False
Direct callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
```
**Symbols:**

```
ffffffff811195f0-ffffffff811196db: irq_set_affinity_notifier (STB_GLOBAL)
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
