# Function: <code>rcu_segcblist_get_seglen</code>

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
In kernel/rcu/rcu_segcblist.c (ffffffff8113547b)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs
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
In kernel/rcu/rcu_segcblist.c (ffffffff81157e28)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs
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
In kernel/rcu/rcu_segcblist.c (ffffffff81181166)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs
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
In kernel/rcu/rcu_segcblist.c (ffffffff811bbac6)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int rcu_segcblist_get_seglen(struct rcu_segcblist *rsclp, int seg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce466)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811cda50-ffffffff811cda96: rcu_segcblist_get_seglen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int rcu_segcblist_get_seglen(struct rcu_segcblist *rsclp, int seg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e3050)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_accelerate
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_advance
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_n_segment_cbs
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811e2690-ffffffff811e26d6: rcu_segcblist_get_seglen (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
