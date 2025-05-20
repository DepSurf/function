# Function: <code>rcu_boot_init_percpu_data</code>

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
In kernel/rcu/tree.c (ffffffff81f7f474)
Location: kernel/rcu/tree.c:4148
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
In kernel/rcu/tree.c (ffffffff81fa8554)
Location: kernel/rcu/tree.c:3742
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
In kernel/rcu/tree.c (ffffffff81fe43c0)
Location: kernel/rcu/tree.c:3740
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff820c4f9e)
Location: kernel/rcu/tree.c:3730
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff826cd6d6)
Location: kernel/rcu/tree.c:3716
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff826f7876)
Location: kernel/rcu/tree.c:3505
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff828aea99)
Location: kernel/rcu/tree.c:3251
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828c756b)
Location: kernel/rcu/tree.c:2938
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828cfb62)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_boot_init_percpu_data(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82cf05a5)
Location: kernel/rcu/tree.c:3707
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init_one
```
**Symbols:**

```
ffffffff82cf05a5-ffffffff82cf0628: rcu_boot_init_percpu_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_boot_init_percpu_data(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82fdcf40)
Location: kernel/rcu/tree.c:4017
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init_one
```
**Symbols:**

```
ffffffff82fdcf40-ffffffff82fdcfe4: rcu_boot_init_percpu_data (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff831e817c)
Location: kernel/rcu/tree.c:4125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff832cc48e)
Location: kernel/rcu/tree.c:4096
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff8347fe42)
Location: kernel/rcu/tree.c:4222
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff83eac5be)
Location: kernel/rcu/tree.c:4114
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff836d1800)
Location: kernel/rcu/tree.c:4263
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_one
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
In kernel/rcu/tree.c (ffffffff83902ec3)
Location: kernel/rcu/tree.c:4382
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800011447300)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (c1521900)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (c00000000136c530)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffe000008be4)
Location: kernel/rcu/tree.c:2992
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff828b885a)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828b0bbf)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828cb796)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828d0b90)
Location: kernel/rcu/tree.c:2992
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
