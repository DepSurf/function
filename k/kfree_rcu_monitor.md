# Function: <code>kfree_rcu_monitor</code>

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
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133fb0)
Location: kernel/rcu/tree.c:3177
Inline: False
```
**Symbols:**

```
ffffffff81133fb0-ffffffff8113412b: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f9e0)
Location: kernel/rcu/tree.c:3407
Inline: False
```
**Symbols:**

```
ffffffff8112f9e0-ffffffff8112fb8a: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112fd70)
Location: kernel/rcu/tree.c:3429
Inline: False
```
**Symbols:**

```
ffffffff8112fd70-ffffffff8112ff1a: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811518c0)
Location: kernel/rcu/tree.c:3328
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
**Symbols:**

```
ffffffff811518c0-ffffffff81151a24: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81179f30)
Location: kernel/rcu/tree.c:3422
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
**Symbols:**

```
ffffffff81179f30-ffffffff8117a0be: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b00d0)
Location: kernel/rcu/tree.c:3152
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
**Symbols:**

```
ffffffff811b00d0-ffffffff811b0243: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811cbae0)
Location: kernel/rcu/tree.c:3142
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
**Symbols:**

```
ffffffff811cbae0-ffffffff811cbf58: kfree_rcu_monitor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfree_rcu_monitor(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811dd7e0)
Location: kernel/rcu/tree.c:3213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_shrink_scan
```
**Symbols:**

```
ffffffff811dd7e0-ffffffff811ddc58: kfree_rcu_monitor (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
