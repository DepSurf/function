# Function: <code>irq_needs_fixup</code>

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
In kernel/irq/cpuhotplug.c (ffffffff810ee76c)
Location: kernel/irq/cpuhotplug.c:18
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
In kernel/irq/cpuhotplug.c (ffffffff810f7233)
Location: kernel/irq/cpuhotplug.c:18
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
In kernel/irq/cpuhotplug.c (ffffffff810ff4df)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff8110acbf)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff8111437f)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff811204df)
Location: kernel/irq/cpuhotplug.c:19
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff8112ca09)
Location: kernel/irq/cpuhotplug.c:20
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff81128439)
Location: kernel/irq/cpuhotplug.c:20
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811286f9)
Location: kernel/irq/cpuhotplug.c:20
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff81148cc9)
Location: kernel/irq/cpuhotplug.c:20
Inline: True
Inline callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool irq_needs_fixup(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/cpuhotplug.c (0)
Location: kernel/irq/cpuhotplug.c:20
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff8116d7b0-ffffffff8116d841: irq_needs_fixup (STB_LOCAL)
ffffffff81e5e255-ffffffff81e5e275: irq_needs_fixup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool irq_needs_fixup(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811a2970)
Location: kernel/irq/cpuhotplug.c:20
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811a2970-ffffffff811a2a37: irq_needs_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool irq_needs_fixup(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811b4870)
Location: kernel/irq/cpuhotplug.c:20
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811b4870-ffffffff811b4937: irq_needs_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool irq_needs_fixup(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/cpuhotplug.c (ffffffff811c46f0)
Location: kernel/irq/cpuhotplug.c:20
Inline: False
Direct callers:
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811c46f0-ffffffff811c47b7: irq_needs_fixup (STB_LOCAL)
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
In kernel/irq/cpuhotplug.c (ffff8000101862a8)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (c03d50e4)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (c0000000001e0b0c)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff81118abf)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff81109b2f)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff811169af)
Location: kernel/irq/cpuhotplug.c:19
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
In kernel/irq/cpuhotplug.c (ffffffff81121fed)
Location: kernel/irq/cpuhotplug.c:19
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
