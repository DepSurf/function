# Function: <code>__sched_clock_work</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4af0)
Location: kernel/sched/clock.c:169
Inline: False
```
**Symbols:**

```
ffffffff810b4af0-ffffffff810b4bb3: __sched_clock_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810bbdf0)
Location: kernel/sched/clock.c:169
Inline: False
```
**Symbols:**

```
ffffffff810bbdf0-ffffffff810bbeb2: __sched_clock_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:157
Inline: False
```
**Symbols:**

```
ffffffff810c3540-ffffffff810c35ca: __sched_clock_work (STB_LOCAL)
ffffffff810c3802-ffffffff810c3843: __sched_clock_work.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:153
Inline: False
```
**Symbols:**

```
ffffffff810cc7f0-ffffffff810cc87a: __sched_clock_work (STB_LOCAL)
ffffffff810ccac2-ffffffff810ccb03: __sched_clock_work.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810d4c10-ffffffff810d4c90: __sched_clock_work (STB_LOCAL)
ffffffff810d4eb2-ffffffff810d4ef0: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810df1d0-ffffffff810df250: __sched_clock_work (STB_LOCAL)
ffffffff810df472-ffffffff810df4b0: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810e74b0-ffffffff810e7530: __sched_clock_work (STB_LOCAL)
ffffffff810e77c2-ffffffff810e7800: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810e50f0-ffffffff810e5170: __sched_clock_work (STB_LOCAL)
ffffffff81bdc775-ffffffff81bdc7b3: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810e70a0-ffffffff810e7120: __sched_clock_work (STB_LOCAL)
ffffffff81bce8f0-ffffffff81bce92e: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810fe670-ffffffff810fe711: __sched_clock_work (STB_LOCAL)
ffffffff81ca61a1-ffffffff81ca61e3: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/clock.c:152
Inline: False
```
**Symbols:**

```
ffffffff8113c570-ffffffff8113c631: __sched_clock_work (STB_LOCAL)
ffffffff81e569df-ffffffff81e56a33: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116cfa0)
Location: kernel/sched/clock.c:152
Inline: False
```
**Symbols:**

```
ffffffff8116cfa0-ffffffff8116d0d4: __sched_clock_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d540)
Location: kernel/sched/clock.c:152
Inline: False
```
**Symbols:**

```
ffffffff8117d540-ffffffff8117d674: __sched_clock_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118b210)
Location: kernel/sched/clock.c:152
Inline: False
```
**Symbols:**

```
ffffffff8118b210-ffffffff8118b344: __sched_clock_work (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810d93c0-ffffffff810d9440: __sched_clock_work (STB_LOCAL)
ffffffff810d9662-ffffffff810d96a0: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810c7da0-ffffffff810c7e20: __sched_clock_work (STB_LOCAL)
ffffffff810c8042-ffffffff810c8080: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810d5700-ffffffff810d5780: __sched_clock_work (STB_LOCAL)
ffffffff810d59a2-ffffffff810d59e0: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __sched_clock_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (0)
Location: kernel/sched/clock.c:154
Inline: False
```
**Symbols:**

```
ffffffff810e0fb0-ffffffff810e1046: __sched_clock_work (STB_LOCAL)
ffffffff810e1292-ffffffff810e12d0: __sched_clock_work.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
