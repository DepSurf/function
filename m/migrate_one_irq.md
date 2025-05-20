# Function: <code>migrate_one_irq</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff810ee744)
Location: kernel/irq/cpuhotplug.c:25
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff810f717c)
Location: kernel/irq/cpuhotplug.c:51
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff810ff4a4)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff8110ac84)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff81114344)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff811204a4)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8112c9a0-ffffffff8112cbbf: migrate_one_irq (STB_LOCAL)
ffffffff8112cdc1-ffffffff8112cdf6: migrate_one_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811283d0-ffffffff811285ef: migrate_one_irq (STB_LOCAL)
ffffffff81be1c6e-ffffffff81be1ca3: migrate_one_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81128690-ffffffff811288b6: migrate_one_irq (STB_LOCAL)
ffffffff81bd3d25-ffffffff81bd3d5d: migrate_one_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81148c60-ffffffff81148e83: migrate_one_irq (STB_LOCAL)
ffffffff81cadd35-ffffffff81cadd6d: migrate_one_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8116d850-ffffffff8116da00: migrate_one_irq (STB_LOCAL)
ffffffff81e5e275-ffffffff81e5e289: migrate_one_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811a2a50)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811a2a50-ffffffff811a2c0d: migrate_one_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811b4950)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811b4950-ffffffff811b4b0d: migrate_one_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool migrate_one_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811c47d0)
Location: kernel/irq/cpuhotplug.c:53
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811c47d0-ffffffff811c498d: migrate_one_irq (STB_LOCAL)
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
In kernel/irq/cpuhotplug.c (ffff800010186288)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (c03d50b4)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (c0000000001e0adc)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
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
In kernel/irq/cpuhotplug.c (ffffffff81118a84)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff81109af4)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff81116974)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
In kernel/irq/cpuhotplug.c (ffffffff81121fb4)
Location: kernel/irq/cpuhotplug.c:52
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
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
