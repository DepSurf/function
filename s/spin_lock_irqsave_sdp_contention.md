# Function: <code>spin_lock_irqsave_sdp_contention</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void spin_lock_irqsave_sdp_contention(struct srcu_data *sdp, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81175bc0)
Location: kernel/rcu/srcutree.c:358
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff81175bc0-ffffffff81175c4f: spin_lock_irqsave_sdp_contention (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void spin_lock_irqsave_sdp_contention(struct srcu_data *sdp, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811aca70)
Location: kernel/rcu/srcutree.c:358
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811aca70-ffffffff811acb0a: spin_lock_irqsave_sdp_contention (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void spin_lock_irqsave_sdp_contention(struct srcu_data *sdp, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811be8f0)
Location: kernel/rcu/srcutree.c:367
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811be8f0-ffffffff811be98c: spin_lock_irqsave_sdp_contention (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void spin_lock_irqsave_sdp_contention(struct srcu_data *sdp, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cee10)
Location: kernel/rcu/srcutree.c:369
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811cee10-ffffffff811ceeac: spin_lock_irqsave_sdp_contention (STB_LOCAL)
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
