# Function: <code>trace_hwlat_sample</code>

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
In kernel/trace/trace_hwlat.c (ffffffff8116d6d6)
Location: kernel/trace/trace_hwlat.c:104
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8117087e)
Location: kernel/trace/trace_hwlat.c:105
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8117da4e)
Location: kernel/trace/trace_hwlat.c:105
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8118cc2f)
Location: kernel/trace/trace_hwlat.c:105
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8119a737)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811a831e)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811b3b1e)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811cbcb0)
Location: kernel/trace/trace_hwlat.c:104
Inline: False
```
**Symbols:**

```
ffffffff811cbcb0-ffffffff811cbd6e: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811c9300)
Location: kernel/trace/trace_hwlat.c:104
Inline: False
```
**Symbols:**

```
ffffffff811c9300-ffffffff811c93be: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811ca700)
Location: kernel/trace/trace_hwlat.c:104
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
```
**Symbols:**

```
ffffffff811ca700-ffffffff811ca7c1: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff811f6470)
Location: kernel/trace/trace_hwlat.c:130
Inline: False
```
**Symbols:**

```
ffffffff811f6470-ffffffff811f6531: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8122fe70)
Location: kernel/trace/trace_hwlat.c:130
Inline: False
```
**Symbols:**

```
ffffffff8122fe70-ffffffff8122ff62: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff8127c070)
Location: kernel/trace/trace_hwlat.c:130
Inline: False
```
**Symbols:**

```
ffffffff8127c070-ffffffff8127c162: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff81293b90)
Location: kernel/trace/trace_hwlat.c:130
Inline: False
```
**Symbols:**

```
ffffffff81293b90-ffffffff81293c82: trace_hwlat_sample (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_hwlat_sample(struct hwlat_sample *sample);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_hwlat.c (ffffffff812af1f0)
Location: kernel/trace/trace_hwlat.c:130
Inline: False
```
**Symbols:**

```
ffffffff812af1f0-ffffffff812af2e2: trace_hwlat_sample (STB_LOCAL)
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
In kernel/trace/trace_hwlat.c (ffff800010231e00)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (c046db94)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (c0000000002bc5e8)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffe000189574)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811ac13e)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff8119f028)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811a9f0e)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
In kernel/trace/trace_hwlat.c (ffffffff811b7d4e)
Location: kernel/trace/trace_hwlat.c:103
Inline: True
Inline callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
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
