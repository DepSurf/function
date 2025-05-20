# Function: <code>spin_lock_irqsave_check_contention</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void spin_lock_irqsave_check_contention(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81175b50)
Location: kernel/rcu/srcutree.c:336
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
**Symbols:**

```
ffffffff81175b50-ffffffff81175bb8: spin_lock_irqsave_check_contention (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void spin_lock_irqsave_check_contention(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ac9f0)
Location: kernel/rcu/srcutree.c:336
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
**Symbols:**

```
ffffffff811ac9f0-ffffffff811aca58: spin_lock_irqsave_check_contention (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void spin_lock_irqsave_check_contention(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811be860)
Location: kernel/rcu/srcutree.c:345
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
**Symbols:**

```
ffffffff811be860-ffffffff811be8de: spin_lock_irqsave_check_contention (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void spin_lock_irqsave_check_contention(struct srcu_struct *ssp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ced80)
Location: kernel/rcu/srcutree.c:347
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:spin_lock_irqsave_ssp_contention
  - kernel/rcu/srcutree.c:spin_lock_irqsave_sdp_contention
```
**Symbols:**

```
ffffffff811ced80-ffffffff811cedfe: spin_lock_irqsave_check_contention (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
