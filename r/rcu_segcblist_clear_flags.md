# Function: <code>rcu_segcblist_clear_flags</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134fb5)
Location: kernel/rcu/rcu_segcblist.h:62
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_offload
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/rcu_segcblist.c (ffffffff811577b5)
Location: kernel/rcu/rcu_segcblist.h:62
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_offload
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/rcu_segcblist.c (ffffffff81180a44)
Location: kernel/rcu/rcu_segcblist.h:62
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_offload
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/rcu_segcblist.c (ffffffff811bb2c4)
Location: kernel/rcu/rcu_segcblist.h:62
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_offload
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/rcu_segcblist.c (ffffffff811cdc64)
Location: kernel/rcu/rcu_segcblist.h:64
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_offload
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/tree.c (ffffffff83903adc)
Location: kernel/rcu/rcu_segcblist.h:64
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:rcu_nocb_rdp_offload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:nocb_cb_wait
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2884)
Location: kernel/rcu/rcu_segcblist.h:64
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_offload
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
