# Function: <code>rcu_nmi_exit_common</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113355)
Location: kernel/rcu/tree.c:666
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
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
In kernel/rcu/tree.c (ffffffff8111cfa5)
Location: kernel/rcu/tree.c:628
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff81129495)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/rcu/tree.c (ffff800010190a18)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
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
In kernel/rcu/tree.c (c03de59c)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
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
In kernel/rcu/tree.c (c0000000001ebe40)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000123fc0)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
```
</details>
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
In kernel/rcu/tree.c (ffffffff81121a75)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff811140e5)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff8111f965)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff8112bad5)
Location: kernel/rcu/tree.c:635
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
```
</details>
</li>
</ul>

## Differences
