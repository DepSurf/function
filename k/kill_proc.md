# Function: <code>kill_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812022b0)
Location: mm/memory-failure.c:181
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812022b0-ffffffff812023ec: kill_proc.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff81226400)
Location: mm/memory-failure.c:181
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81226400-ffffffff8122653c: kill_proc.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812389d0)
Location: mm/memory-failure.c:181
Inline: True
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff812389d0-ffffffff81238b0c: kill_proc.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff81244600)
Location: mm/memory-failure.c:181
Inline: True
```
**Symbols:**

```
ffffffff81244600-ffffffff81244733: kill_proc.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff81264490)
Location: mm/memory-failure.c:181
Inline: True
```
**Symbols:**

```
ffffffff81264490-ffffffff812645c3: kill_proc.isra.15 (STB_LOCAL)
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
In mm/memory-failure.c (ffffffff8128a895)
Location: mm/memory-failure.c:212
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff8129f7fc)
Location: mm/memory-failure.c:213
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff812ba9cf)
Location: mm/memory-failure.c:210
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff812cc8af)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff81302b8d)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff81be9ed1)
Location: mm/memory-failure.c:236
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff81bdbf03)
Location: mm/memory-failure.c:236
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_proc(struct to_kill *tk, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81cc2d74)
Location: mm/memory-failure.c:250
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_accessing_process
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff81cc2d74-ffffffff81cc2e16: kill_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kill_proc(struct to_kill *tk, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81e75301)
Location: mm/memory-failure.c:249
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_accessing_process
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff81e75301-ffffffff81e753af: kill_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kill_proc(struct to_kill *tk, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8145e5d0)
Location: mm/memory-failure.c:271
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_accessing_process
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff8145e5d0-ffffffff8145e695: kill_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kill_proc(struct to_kill *tk, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814943f0)
Location: mm/memory-failure.c:329
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_accessing_process
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff814943f0-ffffffff814944b5: kill_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kill_proc(struct to_kill *tk, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c3c50)
Location: mm/memory-failure.c:328
Inline: False
Direct callers:
  - mm/memory-failure.c:kill_accessing_process
  - mm/memory-failure.c:kill_procs
```
**Symbols:**

```
ffffffff814c3c50-ffffffff814c3d15: kill_proc (STB_LOCAL)
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
In mm/memory-failure.c (ffff80001036f110)
Location: mm/memory-failure.c:209
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045e100)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/memory-failure.c (ffffffff812c4e8f)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff812b5ecf)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff812c2c9f)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
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
In mm/memory-failure.c (ffffffff812d373f)
Location: mm/memory-failure.c:209
Inline: True
Inline callers:
  - mm/memory-failure.c:kill_procs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
