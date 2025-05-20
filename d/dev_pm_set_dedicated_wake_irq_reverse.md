# Function: <code>dev_pm_set_dedicated_wake_irq_reverse</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_pm_set_dedicated_wake_irq_reverse(struct device *dev, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81992a90)
Location: drivers/base/power/wakeirq.c:241
Inline: False
```
**Symbols:**

```
ffffffff81992a90-ffffffff81992aaf: dev_pm_set_dedicated_wake_irq_reverse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_pm_set_dedicated_wake_irq_reverse(struct device *dev, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81b02fd0)
Location: drivers/base/power/wakeirq.c:241
Inline: False
```
**Symbols:**

```
ffffffff81b02fd0-ffffffff81b02fef: dev_pm_set_dedicated_wake_irq_reverse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_pm_set_dedicated_wake_irq_reverse(struct device *dev, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81b50fd0)
Location: drivers/base/power/wakeirq.c:230
Inline: False
```
**Symbols:**

```
ffffffff81b50fd0-ffffffff81b50fef: dev_pm_set_dedicated_wake_irq_reverse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_pm_set_dedicated_wake_irq_reverse(struct device *dev, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeirq.c (ffffffff81ba9580)
Location: drivers/base/power/wakeirq.c:230
Inline: False
```
**Symbols:**

```
ffffffff81ba9580-ffffffff81ba959f: dev_pm_set_dedicated_wake_irq_reverse (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
