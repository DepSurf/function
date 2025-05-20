# Function: <code>irq_spread_init_one</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810efbcf)
Location: kernel/irq/affinity.c:7
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810efb8c)
Location: kernel/irq/affinity.c:10
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff810f8849)
Location: kernel/irq/affinity.c:11
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81100927)
Location: kernel/irq/affinity.c:11
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110c0e6)
Location: kernel/irq/affinity.c:11
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8111585f)
Location: kernel/irq/affinity.c:11
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81121cb1)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask *irqmsk, struct cpumask *nmsk, unsigned int cpus_per_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112df60)
Location: kernel/irq/affinity.c:12
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8112df60-ffffffff8112dff3: irq_spread_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask *irqmsk, struct cpumask *nmsk, unsigned int cpus_per_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81129b50)
Location: kernel/irq/affinity.c:12
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff81129b50-ffffffff81129be3: irq_spread_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask *irqmsk, struct cpumask *nmsk, unsigned int cpus_per_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81129de0)
Location: kernel/irq/affinity.c:12
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff81129de0-ffffffff81129e7f: irq_spread_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask *irqmsk, struct cpumask *nmsk, unsigned int cpus_per_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8114a710)
Location: kernel/irq/affinity.c:12
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8114a710-ffffffff8114a7df: irq_spread_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask *irqmsk, struct cpumask *nmsk, unsigned int cpus_per_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8116fb90)
Location: kernel/irq/affinity.c:12
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff8116fb90-ffffffff8116fc5c: irq_spread_init_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_spread_init_one(struct cpumask *irqmsk, struct cpumask *nmsk, unsigned int cpus_per_vec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811a5fc0)
Location: kernel/irq/affinity.c:12
Inline: False
Direct callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
**Symbols:**

```
ffffffff811a5fc0-ffffffff811a60aa: irq_spread_init_one (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffff800010187e54)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c03d68dc)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c0000000001e1b94)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
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
In kernel/irq/affinity.c (ffffffe00011d676)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8111a291)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8110b301)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81118181)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81123811)
Location: kernel/irq/affinity.c:12
Inline: True
Inline callers:
  - kernel/irq/affinity.c:__irq_build_affinity_masks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
