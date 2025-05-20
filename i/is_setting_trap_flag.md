# Function: <code>is_setting_trap_flag</code>

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
In arch/x86/kernel/step.c (ffffffff8103dd00)
Location: arch/x86/kernel/step.c:54
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8103db20)
Location: arch/x86/kernel/step.c:54
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8103d3fb)
Location: arch/x86/kernel/step.c:54
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8103b44b)
Location: arch/x86/kernel/step.c:55
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8103de6a)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8103f41d)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff81040a1d)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff810430de)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8104383e)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int is_setting_trap_flag(struct task_struct *child, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81046fe0)
Location: arch/x86/kernel/step.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_single_step
```
**Symbols:**

```
ffffffff81046fe0-ffffffff810470e8: is_setting_trap_flag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int is_setting_trap_flag(struct task_struct *child, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81046830)
Location: arch/x86/kernel/step.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_single_step
```
**Symbols:**

```
ffffffff81046830-ffffffff81046938: is_setting_trap_flag (STB_LOCAL)
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
In arch/x86/kernel/step.c (ffffffff81048323)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff8104ec35)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81059e72)
Location: arch/x86/kernel/step.c:56
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810677b1)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_single_step
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8106904d)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_single_step
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810704bd)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_single_step
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
In arch/x86/kernel/step.c (ffffffff810439be)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff81032ffe)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff810437fe)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
In arch/x86/kernel/step.c (ffffffff81044bfe)
Location: arch/x86/kernel/step.c:56
Inline: True
Inline callers:
  - arch/x86/kernel/step.c:enable_step
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
</ul>
