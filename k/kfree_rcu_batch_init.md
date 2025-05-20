# Function: <code>kfree_rcu_batch_init</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kfree_rcu_batch_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82cf07de)
Location: kernel/rcu/tree.c:4248
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff82cf07de-ffffffff82cf08ec: kfree_rcu_batch_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kfree_rcu_batch_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82fdd19a)
Location: kernel/rcu/tree.c:4569
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff82fdd19a-ffffffff82fdd2c8: kfree_rcu_batch_init (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff831e84b5)
Location: kernel/rcu/tree.c:4699
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff832cc8a7)
Location: kernel/rcu/tree.c:4670
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff83480274)
Location: kernel/rcu/tree.c:4858
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff83eacaff)
Location: kernel/rcu/tree.c:4766
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfree_rcu_batch_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff836d0e20)
Location: kernel/rcu/tree.c:4926
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff836d0e20-ffffffff836d106d: kfree_rcu_batch_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfree_rcu_batch_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff83902390)
Location: kernel/rcu/tree.c:5081
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff83902390-ffffffff839025f0: kfree_rcu_batch_init (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
