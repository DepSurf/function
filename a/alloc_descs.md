# Function: <code>alloc_descs</code>

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
In kernel/irq/irqdesc.c (ffffffff81818ed3)
Location: kernel/irq/irqdesc.c:195
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81892b0d)
Location: kernel/irq/irqdesc.c:233
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff818c740b)
Location: kernel/irq/irqdesc.c:421
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff818feb4c)
Location: kernel/irq/irqdesc.c:437
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81988dd5)
Location: kernel/irq/irqdesc.c:433
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff819e56be)
Location: kernel/irq/irqdesc.c:450
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81a208ce)
Location: kernel/irq/irqdesc.c:451
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81a90dfe)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81ac813e)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:466
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff811219c0-ffffffff81121b71: alloc_descs (STB_LOCAL)
ffffffff8112214a-ffffffff8112215e: alloc_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:468
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff8111da20-ffffffff8111dbd1: alloc_descs (STB_LOCAL)
ffffffff81be157d-ffffffff81be1591: alloc_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:468
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff8111dd30-ffffffff8111dee1: alloc_descs (STB_LOCAL)
ffffffff81bd3638-ffffffff81bd364c: alloc_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:468
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff8113e170-ffffffff8113e357: alloc_descs (STB_LOCAL)
ffffffff81cad4a6-ffffffff81cad4ba: alloc_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdesc.c (0)
Location: kernel/irq/irqdesc.c:469
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff81161730-ffffffff8116193f: alloc_descs (STB_LOCAL)
ffffffff81e5d9a3-ffffffff81e5d9b7: alloc_descs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81194dc0)
Location: kernel/irq/irqdesc.c:472
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff81194dc0-ffffffff81194fef: alloc_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a65a0)
Location: kernel/irq/irqdesc.c:493
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff811a65a0-ffffffff811a680a: alloc_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_descs(unsigned int start, unsigned int cnt, int node, const struct irq_affinity_desc *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b60c0)
Location: kernel/irq/irqdesc.c:493
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
```
**Symbols:**

```
ffffffff811b60c0-ffffffff811b632d: alloc_descs (STB_LOCAL)
```
</details>
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
In kernel/irq/irqdesc.c (ffff800010d9bfbc)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (c0e98648)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (c0000000001d1fd0)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffe0008c42aa)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81a66fae)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81a23a6e)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81ad33be)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
In kernel/irq/irqdesc.c (ffffffff81adf8be)
Location: kernel/irq/irqdesc.c:466
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
