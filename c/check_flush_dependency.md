# Function: <code>check_flush_dependency</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109a710)
Location: kernel/workqueue.c:2404
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff8109a710-ffffffff8109a83c: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109fab0)
Location: kernel/workqueue.c:2406
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff8109fab0-ffffffff8109fbdc: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109d230)
Location: kernel/workqueue.c:2405
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff8109d230-ffffffff8109d32a: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4ec0)
Location: kernel/workqueue.c:2421
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810a4ec0-ffffffff810a4fef: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ab000)
Location: kernel/workqueue.c:2468
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810ab000-ffffffff810ab12b: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b4100)
Location: kernel/workqueue.c:2491
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810b4100-ffffffff810b422b: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9d50)
Location: kernel/workqueue.c:2587
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810b9d50-ffffffff810b9e81: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c01d0)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810c01d0-ffffffff810c0301: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c7510)
Location: kernel/workqueue.c:2593
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810c7510-ffffffff810c7635: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2a90)
Location: kernel/workqueue.c:2599
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810c2a90-ffffffff810c2bb5: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c48a0)
Location: kernel/workqueue.c:2600
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810c48a0-ffffffff810c49c5: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2631
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810d74c0-ffffffff810d75fb: check_flush_dependency (STB_LOCAL)
ffffffff81ca511a-ffffffff81ca5144: check_flush_dependency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2614
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_workqueue
```
**Symbols:**

```
ffffffff810f1de0-ffffffff810f1f78: check_flush_dependency (STB_LOCAL)
ffffffff81e54a2e-ffffffff81e54a96: check_flush_dependency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2614
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_workqueue
```
**Symbols:**

```
ffffffff81112c00-ffffffff81112d98: check_flush_dependency (STB_LOCAL)
ffffffff82056550-ffffffff820565b8: check_flush_dependency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2930
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_workqueue
```
**Symbols:**

```
ffffffff8111ef90-ffffffff8111f128: check_flush_dependency (STB_LOCAL)
ffffffff820d4aad-ffffffff820d4adf: check_flush_dependency.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:2952
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_workqueue
```
**Symbols:**

```
ffffffff81129240-ffffffff811293d8: check_flush_dependency (STB_LOCAL)
ffffffff821af9f9-ffffffff821afa2b: check_flush_dependency.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff80001011ca58)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffff80001011ca58-ffff80001011cb80: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0372ce0)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
c0372ce0-c0372e68: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c000000000166bd0)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
c000000000166bd0-c000000000166da8: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000d7246)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffe0000d7246-ffffffe0000d7350: check_flush_dependency (STB_LOCAL)
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
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ba540)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810ba540-ffffffff810ba671: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8e80)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810a8e80-ffffffff810a8fb1: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b9aa0)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810b9aa0-ffffffff810b9bd1: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void check_flush_dependency(struct workqueue_struct *target_wq, struct work_struct *target_work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c2be0)
Location: kernel/workqueue.c:2596
Inline: False
Direct callers:
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:flush_workqueue
```
**Symbols:**

```
ffffffff810c2be0-ffffffff810c2d11: check_flush_dependency (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
