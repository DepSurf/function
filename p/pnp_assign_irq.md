# Function: <code>pnp_assign_irq</code>

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
In drivers/pnp/manager.c (ffffffff814b988f)
Location: drivers/pnp/manager.c:131
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815091ab)
Location: drivers/pnp/manager.c:131
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8152d3cb)
Location: drivers/pnp/manager.c:131
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff81540488)
Location: drivers/pnp/manager.c:131
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815a35a8)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815db390)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff815f4b40)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff81626af6)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff816485e6)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff816f7170)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff816f7170-ffffffff816f72de: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff81713f30)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff81713f30-ffffffff8171409e: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff816f53c0)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff816f53c0-ffffffff816f5536: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff8176f990)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff8176f990-ffffffff8176fb3f: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff818a4da0)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff818a4da0-ffffffff818a4f77: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff819eeb90)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff819eeb90-ffffffff819eed7d: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff81a37360)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff81a37360-ffffffff81a3754d: pnp_assign_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pnp_assign_irq(struct pnp_dev *dev, struct pnp_irq *rule, int idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/manager.c (ffffffff81a82b20)
Location: drivers/pnp/manager.c:132
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
**Symbols:**

```
ffffffff81a82b20-ffffffff81a82d0d: pnp_assign_irq (STB_LOCAL)
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
In drivers/pnp/manager.c (ffff8000107b5800)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/pnp/manager.c (ffffffff8160e646)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff81602b96)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff8163c426)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
In drivers/pnp/manager.c (ffffffff81656776)
Location: drivers/pnp/manager.c:132
Inline: True
Inline callers:
  - drivers/pnp/manager.c:pnp_assign_resources
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
