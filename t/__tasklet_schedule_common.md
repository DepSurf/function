# Function: <code>__tasklet_schedule_common</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094c20)
Location: kernel/softirq.c:470
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff81094c20-ffffffff81094cef: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d030)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__hrtimer_tasklet_trampoline
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff8109d030-ffffffff8109d0ff: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1710)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810a1710-ffffffff810a17df: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a7cd0)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810a7cd0-ffffffff810a7d9f: __tasklet_schedule_common (STB_LOCAL)
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
In kernel/softirq.c (ffffffff810af485)
Location: kernel/softirq.c:498
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
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
In kernel/softirq.c (ffffffff810aac25)
Location: kernel/softirq.c:502
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
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
In kernel/softirq.c (ffffffff810abfb5)
Location: kernel/softirq.c:719
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
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
In kernel/softirq.c (ffffffff810bdc35)
Location: kernel/softirq.c:718
Inline: True
Inline callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4c70)
Location: kernel/softirq.c:732
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810d4c70-ffffffff810d4cee: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3c70)
Location: kernel/softirq.c:732
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810f3c70-ffffffff810f3d01: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811000a0)
Location: kernel/softirq.c:714
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff811000a0-ffffffff81100131: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811097c0)
Location: kernel/softirq.c:714
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff811097c0-ffffffff81109851: __tasklet_schedule_common (STB_LOCAL)
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
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff590)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffff8000100ff590-ffff8000100ff620: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035c1d4)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
c035c1d4-c035c250: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000146940)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
c000000000146940-c0000000001469f4: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c73c6)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffe0000c73c6-ffffffe0000c744e: __tasklet_schedule_common (STB_LOCAL)
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
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a15f0)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810a15f0-ffffffff810a16bf: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108ffe0)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff8108ffe0-ffffffff81090098: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a15a0)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810a15a0-ffffffff810a166f: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __tasklet_schedule_common(struct tasklet_struct *t, struct tasklet_head *headp, unsigned int softirq_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a9540)
Location: kernel/softirq.c:471
Inline: False
Direct callers:
  - kernel/softirq.c:__tasklet_hi_schedule
  - kernel/softirq.c:__tasklet_schedule
```
**Symbols:**

```
ffffffff810a9540-ffffffff810a9628: __tasklet_schedule_common (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
