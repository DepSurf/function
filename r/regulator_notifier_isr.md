# Function: <code>regulator_notifier_isr</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t regulator_notifier_isr(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (0)
Location: drivers/regulator/irq_helpers.c:156
Inline: False
```
**Symbols:**

```
ffffffff817b2370-ffffffff817b262c: regulator_notifier_isr (STB_LOCAL)
ffffffff81cf8476-ffffffff81cf84a2: regulator_notifier_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t regulator_notifier_isr(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (0)
Location: drivers/regulator/irq_helpers.c:156
Inline: False
```
**Symbols:**

```
ffffffff818edd00-ffffffff818edfa0: regulator_notifier_isr (STB_LOCAL)
ffffffff81ec0573-ffffffff81ec059f: regulator_notifier_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t regulator_notifier_isr(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (0)
Location: drivers/regulator/irq_helpers.c:156
Inline: False
```
**Symbols:**

```
ffffffff81a45860-ffffffff81a45ad6: regulator_notifier_isr (STB_LOCAL)
ffffffff82094ce9-ffffffff82094d1d: regulator_notifier_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t regulator_notifier_isr(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (0)
Location: drivers/regulator/irq_helpers.c:156
Inline: False
```
**Symbols:**

```
ffffffff81a8fa10-ffffffff81a8fc86: regulator_notifier_isr (STB_LOCAL)
ffffffff82115b0e-ffffffff82115b42: regulator_notifier_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t regulator_notifier_isr(int irq, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/regulator/irq_helpers.c (0)
Location: drivers/regulator/irq_helpers.c:156
Inline: False
```
**Symbols:**

```
ffffffff81ae2280-ffffffff81ae2500: regulator_notifier_isr (STB_LOCAL)
ffffffff821f3814-ffffffff821f3848: regulator_notifier_isr.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
