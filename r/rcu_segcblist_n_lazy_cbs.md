# Function: <code>rcu_segcblist_n_lazy_cbs</code>

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
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:84
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
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:62
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
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:62
Inline: True
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
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:62
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:49
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (c03e04b4)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:63
Inline: True
```
</details>
</li>
</ul>

## Differences
