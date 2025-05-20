# Function: <code>ksoftirqd_running</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d9f9)
Location: kernel/softirq.c:84
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
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
In kernel/softirq.c (ffffffff8108aa29)
Location: kernel/softirq.c:84
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
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
In kernel/softirq.c (ffffffff810916f9)
Location: kernel/softirq.c:84
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
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
In kernel/softirq.c (ffffffff810951cb)
Location: kernel/softirq.c:86
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
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
In kernel/softirq.c (ffffffff8109d543)
Location: kernel/softirq.c:86
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a10b0)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff810a10b0-ffffffff810a10e5: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a7670)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff810a7670-ffffffff810a76a5: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af9c2)
Location: kernel/softirq.c:85
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
In kernel/softirq.c (ffffffff810ab152)
Location: kernel/softirq.c:85
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
In kernel/softirq.c (ffffffff810ac342)
Location: kernel/softirq.c:89
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
In kernel/softirq.c (ffffffff810bd9a2)
Location: kernel/softirq.c:89
Inline: True
Inline callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
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
In kernel/softirq.c (ffffffff810d4618)
Location: kernel/softirq.c:89
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
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
In kernel/softirq.c (ffffffff810f3503)
Location: kernel/softirq.c:89
Inline: True
Inline callers:
  - kernel/softirq.c:__irq_exit_rcu
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100fec10)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffff8000100fec10-ffff8000100fec8c: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035b758)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
c035b758-c035b7b4: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000145a90)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
c000000000145a90-c000000000145b08: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c6c6c)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffe0000c6c6c-ffffffe0000c6cd8: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a0f90)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff810a0f90-ffffffff810a0fc5: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108f9b0)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff8108f9b0-ffffffff8108f9e5: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a0f40)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff810a0f40-ffffffff810a0f75: ksoftirqd_running (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ksoftirqd_running(long unsigned int pending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a8ec0)
Location: kernel/softirq.c:85
Inline: False
Direct callers:
  - kernel/softirq.c:irq_exit
```
**Symbols:**

```
ffffffff810a8ec0-ffffffff810a8ef5: ksoftirqd_running (STB_LOCAL)
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
