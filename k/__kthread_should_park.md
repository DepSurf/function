# Function: <code>__kthread_should_park</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (ffffffff810c2893)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffff810c32e4-ffffffff810c32f7: __kthread_should_park.cold (STB_LOCAL)
ffffffff810c2820-ffffffff810c284b: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c7e9f)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffff810c7e60-ffffffff810c7e86: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d077f)
Location: kernel/kthread.c:114
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810d06d0-ffffffff810d06f6: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb19f)
Location: kernel/kthread.c:115
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810cb0f0-ffffffff810cb116: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ccb0f)
Location: kernel/kthread.c:140
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810cca60-ffffffff810cca86: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810df65f)
Location: kernel/kthread.c:140
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
```
**Symbols:**

```
ffffffff810df620-ffffffff810df646: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f96af)
Location: kernel/kthread.c:161
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:__irq_exit_rcu
```
**Symbols:**

```
ffffffff810f9670-ffffffff810f969c: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c32f)
Location: kernel/kthread.c:161
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:__irq_exit_rcu
```
**Symbols:**

```
ffffffff8111c2e0-ffffffff8111c30c: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112957f)
Location: kernel/kthread.c:162
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
```
**Symbols:**

```
ffffffff81129530-ffffffff8112955c: __kthread_should_park (STB_GLOBAL)
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
In kernel/kthread.c (ffffffff81133bbf)
Location: kernel/kthread.c:162
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff80001012716c)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffff800010127100-ffff800010127154: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379aa0)
Location: kernel/kthread.c:107
Inline: False
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
  - kernel/kthread.c:kthread_should_park
```
**Symbols:**

```
c0379aa0-c0379aec: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000172f6c)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
c000000000172f00-c000000000172f28: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000de9a6)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffe0000de95c-ffffffe0000de994: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c221f)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffff810c21e0-ffffffff810c2206: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0a6f)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffff810b0a30-ffffffff810b0a56: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c176f)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffff810c1730-ffffffff810c1756: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __kthread_should_park(struct task_struct *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9b9f)
Location: kernel/kthread.c:107
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_should_park
Direct callers:
  - kernel/softirq.c:ksoftirqd_running
```
**Symbols:**

```
ffffffff810c9b60-ffffffff810c9b86: __kthread_should_park (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
