# Function: <code>irq_build_affinity_masks</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811006a0)
Location: kernel/irq/affinity.c:97
Inline: True
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff811006a0-ffffffff81100af3: irq_build_affinity_masks.isra.0 (STB_LOCAL)
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
In kernel/irq/affinity.c (ffffffff8110c48c)
Location: kernel/irq/affinity.c:176
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81115b47)
Location: kernel/irq/affinity.c:173
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81121f57)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112e410)
Location: kernel/irq/affinity.c:338
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff8112e410-ffffffff8112e654: irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112a000)
Location: kernel/irq/affinity.c:338
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff8112a000-ffffffff8112a244: irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8112a280)
Location: kernel/irq/affinity.c:338
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff8112a280-ffffffff8112a4c1: irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff8114abe0)
Location: kernel/irq/affinity.c:338
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff8114abe0-ffffffff8114ae57: irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff81170230)
Location: kernel/irq/affinity.c:339
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff81170230-ffffffff811704c7: irq_build_affinity_masks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (ffffffff811a6690)
Location: kernel/irq/affinity.c:339
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
ffffffff811a6690-ffffffff811a693f: irq_build_affinity_masks (STB_LOCAL)
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
In kernel/irq/affinity.c (ffff8000101881ac)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (c03d6bc4)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_build_affinity_masks(unsigned int startvec, unsigned int numvecs, unsigned int firstvec, struct irq_affinity_desc *masks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/affinity.c (c0000000001e1ec0)
Location: kernel/irq/affinity.c:338
Inline: False
Direct callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
```
**Symbols:**

```
c0000000001e1ec0-c0000000001e2188: irq_build_affinity_masks (STB_LOCAL)
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
In kernel/irq/affinity.c (ffffffe00011d934)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8111a537)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff8110b5a7)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81118427)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
In kernel/irq/affinity.c (ffffffff81123ab7)
Location: kernel/irq/affinity.c:338
Inline: True
Inline callers:
  - kernel/irq/affinity.c:irq_create_affinity_masks
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
<b>Arch</b>
<ul>
</ul>
