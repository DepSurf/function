# Function: <code>irq_do_set_affinity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dbf20)
Location: kernel/irq/manage.c:190
Inline: False
Direct callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/migration.c:irq_move_masked_irq
```
**Symbols:**

```
ffffffff810dbf20-ffffffff810dbf9c: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1630)
Location: kernel/irq/manage.c:203
Inline: False
Direct callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/migration.c:irq_move_masked_irq
```
**Symbols:**

```
ffffffff810e1630-ffffffff810e16ac: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7f90)
Location: kernel/irq/manage.c:203
Inline: False
Direct callers:
  - kernel/irq/manage.c:setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/migration.c:irq_move_masked_irq
```
**Symbols:**

```
ffffffff810e7f90-ffffffff810e8003: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e74e0)
Location: kernel/irq/manage.c:177
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810e74e0-ffffffff810e7553: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810ef7f0)
Location: kernel/irq/manage.c:190
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810ef7f0-ffffffff810ef8cf: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:190
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff810f8edf-ffffffff810f8efe: irq_do_set_affinity.cold.49 (STB_LOCAL)
ffffffff810f7be0-ffffffff810f7cb3: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:190
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8110467f-ffffffff8110469e: irq_do_set_affinity.cold.49 (STB_LOCAL)
ffffffff81103330-ffffffff81103403: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8110d752-ffffffff8110d771: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff8110bd20-ffffffff8110bdf1: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81119ad4-ffffffff81119af3: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff81118120-ffffffff811181f1: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:227
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff811259fe-ffffffff81125a1d: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff81123880-ffffffff81123a12: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:227
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81be1736-ffffffff81be1755: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff8111f6d0-ffffffff8111f862: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:227
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81bd37f1-ffffffff81bd3810: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff8111f990-ffffffff8111fb22: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:220
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81cad67a-ffffffff81cad6ae: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff8113fe20-ffffffff8113ffc1: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:220
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff81e5db9a-ffffffff81e5dbce: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff811636a0-ffffffff811638ca: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:212
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff82059956-ffffffff8205996b: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff81197340-ffffffff81197589: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:215
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff820d7ffe-ffffffff820d802e: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff811a8ed0-ffffffff811a9128: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:217
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:migrate_one_irq
```
**Symbols:**

```
ffffffff821b327f-ffffffff821b32af: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff811b8a30-ffffffff811b8c88: irq_do_set_affinity (STB_GLOBAL)
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
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017a980)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffff80001017a980-ffff80001017aa60: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cbc38)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
c03cbc38-c03cbcec: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d4e50)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
c0000000001d4e50-c0000000001d4f50: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114790)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffe000114790-ffffffe000114852: irq_do_set_affinity (STB_GLOBAL)
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
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff811120b4-ffffffff811120d3: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff81110700-ffffffff811107d1: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff81102de4-ffffffff81102e03: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff81101430-ffffffff81101501: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8110ffa4-ffffffff8110ffc3: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff8110e5f0-ffffffff8110e6c1: irq_do_set_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int irq_do_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:216
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_setup_affinity
  - kernel/irq/manage.c:irq_set_affinity_locked
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/migration.c:irq_move_masked_irq
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
  - kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu
```
**Symbols:**

```
ffffffff8111b514-ffffffff8111b533: irq_do_set_affinity.cold (STB_LOCAL)
ffffffff81119b20-ffffffff81119bf1: irq_do_set_affinity (STB_GLOBAL)
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
