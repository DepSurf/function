# Function: <code>sum_vm_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ac680)
Location: mm/vmstat.c:37
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff811ac680-ffffffff811ac71b: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c5510)
Location: mm/vmstat.c:37
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff811c5510-ffffffff811c55a4: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d5620)
Location: mm/vmstat.c:37
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff811d5620-ffffffff811d56b6: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811de3a0)
Location: mm/vmstat.c:37
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff811de3a0-ffffffff811de435: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f3e60)
Location: mm/vmstat.c:110
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff811f3e60-ffffffff811f3eeb: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812152b0)
Location: mm/vmstat.c:110
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff812152b0-ffffffff8121533c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81228190)
Location: mm/vmstat.c:110
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff81228190-ffffffff8122821c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81237da0)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff81237da0-ffffffff81237e2c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81246050)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff81246050-ffffffff812460dc: sum_vm_events (STB_LOCAL)
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
In mm/vmstat.c (ffffffff81273d1b)
Location: mm/vmstat.c:111
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff8127e57b)
Location: mm/vmstat.c:111
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff812836db)
Location: mm/vmstat.c:111
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff812c1935)
Location: mm/vmstat.c:110
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff8131ea53)
Location: mm/vmstat.c:111
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff81393ce3)
Location: mm/vmstat.c:110
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff813c6465)
Location: mm/vmstat.c:111
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
In mm/vmstat.c (ffffffff813f0e65)
Location: mm/vmstat.c:110
Inline: True
Inline callers:
  - mm/vmstat.c:all_vm_events
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
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102d96b0)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffff8000102d96b0-ffff8000102d976c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0500744)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
c0500744-c05007d0: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c000000000399390)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
c000000000399390-c000000000399488: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f3904)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffe0001f3904-ffffffe0001f39bc: sum_vm_events (STB_LOCAL)
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
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e6a0)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff8123e6a0-ffffffff8123e72c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812316a0)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff812316a0-ffffffff8123172c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123c440)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff8123c440-ffffffff8123c4cc: sum_vm_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sum_vm_events(long unsigned int *ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124bba0)
Location: mm/vmstat.c:111
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
```
**Symbols:**

```
ffffffff8124bba0-ffffffff8124bc2c: sum_vm_events (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
