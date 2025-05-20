# Function: <code>irq_setup_affinity</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7710)
Location: kernel/irq/manage.c:326
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff810e7710-ffffffff810e782f: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810efa90)
Location: kernel/irq/manage.c:343
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff810efa90-ffffffff810efbaf: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f7ec0)
Location: kernel/irq/manage.c:376
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff810f7ec0-ffffffff810f7fe5: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:376
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff8110469e-ffffffff811046aa: irq_setup_affinity.cold.50 (STB_LOCAL)
ffffffff81103610-ffffffff8110378b: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:405
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_select_affinity_usr
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff8110d771-ffffffff8110d77d: irq_setup_affinity.cold (STB_LOCAL)
ffffffff8110c030-ffffffff8110c1bc: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81119af3-ffffffff81119aff: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81118460-ffffffff811185ec: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:488
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81125a1d-ffffffff81125a29: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81123d50-ffffffff81123edd: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:558
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81be1755-ffffffff81be1761: irq_setup_affinity.cold (STB_LOCAL)
ffffffff8111fbb0-ffffffff8111fd3d: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:558
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81bd3810-ffffffff81bd381c: irq_setup_affinity.cold (STB_LOCAL)
ffffffff8111fe60-ffffffff8111ffe6: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:582
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81cad6ae-ffffffff81cad6ba: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81140370-ffffffff81140513: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:597
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81e5dbce-ffffffff81e5dbda: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81163cd0-ffffffff81163e88: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811979f0)
Location: kernel/irq/manage.c:589
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff811979f0-ffffffff81197bb6: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a96b0)
Location: kernel/irq/manage.c:592
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff811a96b0-ffffffff811a9876: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b9210)
Location: kernel/irq/manage.c:594
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff811b9210-ffffffff811b93d6: irq_setup_affinity (STB_GLOBAL)
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
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017acc0)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffff80001017acc0-ffff80001017ae84: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cbed4)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
c03cbed4-c03cbfe8: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d5230)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
c0000000001d5230-c0000000001d5450: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe0001149e2)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffe0001149e2-ffffffe000114b04: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff811120d3-ffffffff811120df: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81110a40-ffffffff81110bcc: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff81102e03-ffffffff81102e0f: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81101770-ffffffff811018fc: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff8110ffc3-ffffffff8110ffcf: irq_setup_affinity.cold (STB_LOCAL)
ffffffff8110e930-ffffffff8110eabc: irq_setup_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int irq_setup_affinity(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:412
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff8111b533-ffffffff8111b53f: irq_setup_affinity.cold (STB_LOCAL)
ffffffff81119e60-ffffffff81119fe3: irq_setup_affinity (STB_GLOBAL)
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
