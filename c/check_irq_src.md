# Function: <code>check_irq_src</code>

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
In arch/x86/kernel/mpparse.c (ffffffff81f708b0)
Location: arch/x86/kernel/mpparse.c:680
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff81f98fdf)
Location: arch/x86/kernel/mpparse.c:679
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff81fd44a8)
Location: arch/x86/kernel/mpparse.c:682
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff820b5196)
Location: arch/x86/kernel/mpparse.c:682
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff826bb912)
Location: arch/x86/kernel/mpparse.c:699
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff826e55ed)
Location: arch/x86/kernel/mpparse.c:703
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff8289c128)
Location: arch/x86/kernel/mpparse.c:702
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b3def)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b7246)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_irq_src(struct mpc_intsrc *m, int *nr_m_spare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82cdbc0e)
Location: arch/x86/kernel/mpparse.c:700
Inline: False
```
**Symbols:**

```
ffffffff82cdbc0e-ffffffff82cdbd00: check_irq_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_irq_src(struct mpc_intsrc *m, int *nr_m_spare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff82fc8111)
Location: arch/x86/kernel/mpparse.c:682
Inline: False
```
**Symbols:**

```
ffffffff82fc8111-ffffffff82fc8203: check_irq_src (STB_LOCAL)
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
In arch/x86/kernel/mpparse.c (ffffffff831d3057)
Location: arch/x86/kernel/mpparse.c:682
Inline: True
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
In arch/x86/kernel/mpparse.c (ffffffff832b59b1)
Location: arch/x86/kernel/mpparse.c:683
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void check_irq_src(struct mpc_intsrc *m, int *nr_m_spare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83466d2c)
Location: arch/x86/kernel/mpparse.c:683
Inline: False
```
**Symbols:**

```
ffffffff83466d2c-ffffffff83466f51: check_irq_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_irq_src(struct mpc_intsrc *m, int *nr_m_spare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff83e8ab50)
Location: arch/x86/kernel/mpparse.c:683
Inline: False
```
**Symbols:**

```
ffffffff83e8ab50-ffffffff83e8ae2b: check_irq_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_irq_src(struct mpc_intsrc *m, int *nr_m_spare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff836ae220)
Location: arch/x86/kernel/mpparse.c:683
Inline: False
```
**Symbols:**

```
ffffffff836ae220-ffffffff836ae538: check_irq_src (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_irq_src(struct mpc_intsrc *m, int *nr_m_spare);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff838de7a0)
Location: arch/x86/kernel/mpparse.c:671
Inline: False
```
**Symbols:**

```
ffffffff838de7a0-ffffffff838deab8: check_irq_src (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/mpparse.c (ffffffff828a524d)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff8289d38f)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b815d)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
In arch/x86/kernel/mpparse.c (ffffffff828b825e)
Location: arch/x86/kernel/mpparse.c:700
Inline: True
Inline callers:
  - arch/x86/kernel/mpparse.c:update_mp_table
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
