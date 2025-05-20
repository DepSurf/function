# Function: <code>__irq_exit_rcu</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af955)
Location: kernel/softirq.c:407
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab0e5)
Location: kernel/softirq.c:410
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
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
In kernel/softirq.c (ffffffff810ac2d5)
Location: kernel/softirq.c:627
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
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
In kernel/softirq.c (ffffffff810bd935)
Location: kernel/softirq.c:626
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __irq_exit_rcu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d45b0)
Location: kernel/softirq.c:640
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810d45b0-ffffffff810d466a: __irq_exit_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __irq_exit_rcu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3480)
Location: kernel/softirq.c:640
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810f3480-ffffffff810f3549: __irq_exit_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __irq_exit_rcu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ff8b0)
Location: kernel/softirq.c:622
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810ff8b0-ffffffff810ff950: __irq_exit_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __irq_exit_rcu();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:622
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff81108f60-ffffffff81109053: __irq_exit_rcu (STB_LOCAL)
ffffffff821af1e2-ffffffff821af1f7: __irq_exit_rcu.cold (STB_LOCAL)
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
