# Function: <code>enable_dynirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8300)
Location: drivers/xen/events/events_base.c:1340
Inline: False
```
**Symbols:**

```
ffffffff814c8300-ffffffff814c8325: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518dc0)
Location: drivers/xen/events/events_base.c:1352
Inline: False
```
**Symbols:**

```
ffffffff81518dc0-ffffffff81518de5: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545290)
Location: drivers/xen/events/events_base.c:1347
Inline: False
```
**Symbols:**

```
ffffffff81545290-ffffffff815452b5: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559160)
Location: drivers/xen/events/events_base.c:1346
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81559160-ffffffff81559183: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd550)
Location: drivers/xen/events/events_base.c:1346
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff815bd550-ffffffff815bd579: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5bf0)
Location: drivers/xen/events/events_base.c:1344
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff815f5bf0-ffffffff815f5c19: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610cb0)
Location: drivers/xen/events/events_base.c:1344
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81610cb0-ffffffff81610cd9: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81644a00)
Location: drivers/xen/events/events_base.c:1353
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81644a00-ffffffff81644a29: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81666fb0)
Location: drivers/xen/events/events_base.c:1353
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81666fb0-ffffffff81666fd9: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716485)
Location: drivers/xen/events/events_base.c:1355
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81716560-ffffffff817165c2: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817330e5)
Location: drivers/xen/events/events_base.c:1816
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81733210-ffffffff81733291: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716b95)
Location: drivers/xen/events/events_base.c:1858
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81716cc0-ffffffff81716d41: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81793e95)
Location: drivers/xen/events/events_base.c:1864
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff817940a0-ffffffff81794139: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cc9c5)
Location: drivers/xen/events/events_base.c:1864
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff818ccb60-ffffffff818ccc14: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1e015)
Location: drivers/xen/events/events_base.c:1866
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81a1e2b0-ffffffff81a1e364: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a67215)
Location: drivers/xen/events/events_base.c:1863
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81a67590-ffffffff81a67644: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81aba6c5)
Location: drivers/xen/events/events_base.c:1841
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff81aba880-ffffffff81aba934: enable_dynirq (STB_LOCAL)
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
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830c88)
Location: drivers/xen/events/events_base.c:1353
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffff800010830c88-ffff800010830cc8: enable_dynirq (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162cce0)
Location: drivers/xen/events/events_base.c:1357
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff8162cce0-ffffffff8162cd09: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165adf0)
Location: drivers/xen/events/events_base.c:1353
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff8165adf0-ffffffff8165ae19: enable_dynirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enable_dynirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816753e0)
Location: drivers/xen/events/events_base.c:1353
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:enable_pirq
```
**Symbols:**

```
ffffffff816753e0-ffffffff81675409: enable_dynirq (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
