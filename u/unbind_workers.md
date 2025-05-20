# Function: <code>unbind_workers</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8f11)
Location: kernel/workqueue.c:4542
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810af633)
Location: kernel/workqueue.c:4661
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810b87a3)
Location: kernel/workqueue.c:4684
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810be2b1)
Location: kernel/workqueue.c:4829
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810c4851)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unbind_workers(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c80f0)
Location: kernel/workqueue.c:4886
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
```
**Symbols:**

```
ffffffff810c80f0-ffffffff810c8207: unbind_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unbind_workers(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c3210)
Location: kernel/workqueue.c:4899
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
```
**Symbols:**

```
ffffffff810c3210-ffffffff810c336d: unbind_workers (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810c8e27)
Location: kernel/workqueue.c:4906
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810dba57)
Location: kernel/workqueue.c:4959
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unbind_workers(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f0380)
Location: kernel/workqueue.c:4961
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
```
**Symbols:**

```
ffffffff810f0380-ffffffff810f056c: unbind_workers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unbind_workers(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81111c40)
Location: kernel/workqueue.c:4970
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
```
**Symbols:**

```
ffffffff81111c40-ffffffff81111e2c: unbind_workers (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff81124887)
Location: kernel/workqueue.c:5368
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff8112f0ad)
Location: kernel/workqueue.c:5391
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffff800010122c44)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (c03765c8)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (c00000000016c980)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffe0000db586)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810bebc1)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810ad3f1)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810be121)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
In kernel/workqueue.c (ffffffff810c6491)
Location: kernel/workqueue.c:4863
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_offline_cpu
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
