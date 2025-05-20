# Function: <code>rcu_init_levelspread</code>

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
In kernel/rcu/tree.c (ffffffff81f7f299)
Location: kernel/rcu/tree.c:4364
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
In kernel/rcu/tree.c (ffffffff81fa8301)
Location: kernel/rcu/tree.c:3982
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff81fe4172)
Location: kernel/rcu/tree.c:4008
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f10c4)
Location: kernel/rcu/rcu.h:250
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff820c4d4c)
Location: kernel/rcu/rcu.h:250
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fae52)
Location: kernel/rcu/rcu.h:269
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff826cd41c)
Location: kernel/rcu/rcu.h:269
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110330a)
Location: kernel/rcu/rcu.h:252
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff826f75e0)
Location: kernel/rcu/rcu.h:252
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110ecba)
Location: kernel/rcu/rcu.h:314
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828ae804)
Location: kernel/rcu/rcu.h:314
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffff8111834e)
Location: kernel/rcu/rcu.h:297
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828c72db)
Location: kernel/rcu/rcu.h:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffff8112471e)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828cf8d1)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (ffffffff82cf0c52)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (ffffffff82fdd62e)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (ffffffff831e7ece)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu.h:288
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:292
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu.h:292
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:303
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu.h:303
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:342
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu.h:342
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/rcu.h:351
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
```
```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/rcu.h:351
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
```
</details>
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
In kernel/rcu/srcutree.c (ffff800010189f74)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffff800011447098)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (c03d8718)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (c1521720)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (c0000000001e441c)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (c00000000136c1e4)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffe00011ee5e)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffe000008ace)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffff8111ccfe)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828b85c9)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffff8110ddbe)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828b0902)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffff8111abee)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828cb505)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/srcutree.c (ffffffff811264ce)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/rcu/tree.c (ffffffff828d08ff)
Location: kernel/rcu/rcu.h:298
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
</ul>

## Differences
