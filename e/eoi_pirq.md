# Function: <code>eoi_pirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8370)
Location: drivers/xen/events/events_base.c:481
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:mask_ack_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff814c8370-ffffffff814c842c: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518e30)
Location: drivers/xen/events/events_base.c:481
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81518e30-ffffffff81518f2e: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545300)
Location: drivers/xen/events/events_base.c:480
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81545300-ffffffff815453fe: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815591e0)
Location: drivers/xen/events/events_base.c:472
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff815591e0-ffffffff815592c8: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd5d0)
Location: drivers/xen/events/events_base.c:472
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff815bd5d0-ffffffff815bd6df: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5c70)
Location: drivers/xen/events/events_base.c:472
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff815f5c70-ffffffff815f5d7f: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610d30)
Location: drivers/xen/events/events_base.c:472
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81610d30-ffffffff81610e3f: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:473
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81644a80-ffffffff81644b74: eoi_pirq (STB_LOCAL)
ffffffff81646407-ffffffff8164641a: eoi_pirq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667030)
Location: drivers/xen/events/events_base.c:473
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81667030-ffffffff81667123: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716dc0)
Location: drivers/xen/events/events_base.c:487
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81716dc0-ffffffff81716eb3: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733790)
Location: drivers/xen/events/events_base.c:817
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81733790-ffffffff81733879: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717240)
Location: drivers/xen/events/events_base.c:848
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81717240-ffffffff81717329: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817947b0)
Location: drivers/xen/events/events_base.c:848
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff817947b0-ffffffff81794948: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cd410)
Location: drivers/xen/events/events_base.c:848
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff818cd410-ffffffff818cd5bc: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1e9f0)
Location: drivers/xen/events/events_base.c:850
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81a1e9f0-ffffffff81a1eb9c: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a67bf0)
Location: drivers/xen/events/events_base.c:842
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81a67bf0-ffffffff81a67d7c: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ab9e40)
Location: drivers/xen/events/events_base.c:830
Inline: False
```
**Symbols:**

```
ffffffff81ab9e40-ffffffff81ab9eb3: eoi_pirq (STB_LOCAL)
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
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830d68)
Location: drivers/xen/events/events_base.c:473
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffff800010830d68-ffff800010830e74: eoi_pirq (STB_LOCAL)
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
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162cd60)
Location: drivers/xen/events/events_base.c:477
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff8162cd60-ffffffff8162ce53: eoi_pirq (STB_LOCAL)
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
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165ae70)
Location: drivers/xen/events/events_base.c:473
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff8165ae70-ffffffff8165af63: eoi_pirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void eoi_pirq(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675460)
Location: drivers/xen/events/events_base.c:473
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:mask_ack_pirq
```
**Symbols:**

```
ffffffff81675460-ffffffff81675553: eoi_pirq (STB_LOCAL)
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
