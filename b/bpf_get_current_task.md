# Function: <code>bpf_get_current_task</code>

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
u64 bpf_get_current_task(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81173d60)
Location: kernel/trace/bpf_trace.c:368
Inline: False
```
**Symbols:**

```
ffffffff81173d60-ffffffff81173d6f: bpf_get_current_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117f530)
Location: kernel/trace/bpf_trace.c:362
Inline: False
```
**Symbols:**

```
ffffffff8117f530-ffffffff8117f53f: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182210)
Location: kernel/trace/bpf_trace.c:396
Inline: False
```
**Symbols:**

```
ffffffff81182210-ffffffff8118221f: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fbd0)
Location: kernel/trace/bpf_trace.c:440
Inline: False
```
**Symbols:**

```
ffffffff8118fbd0-ffffffff8118fbdf: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4550)
Location: kernel/trace/bpf_trace.c:463
Inline: False
```
**Symbols:**

```
ffffffff811a4550-ffffffff811a455f: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b2680)
Location: kernel/trace/bpf_trace.c:499
Inline: False
```
**Symbols:**

```
ffffffff811b2680-ffffffff811b268f: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c0f40)
Location: kernel/trace/bpf_trace.c:533
Inline: False
```
**Symbols:**

```
ffffffff811c0f40-ffffffff811c0f4a: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cc6f0)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
ffffffff811cc6f0-ffffffff811cc6fa: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e80c0)
Location: kernel/trace/bpf_trace.c:941
Inline: False
```
**Symbols:**

```
ffffffff811e80c0-ffffffff811e80ca: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e5ac0)
Location: kernel/trace/bpf_trace.c:1024
Inline: True
```
**Symbols:**

```
ffffffff811e5ac0-ffffffff811e5aca: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e71d0)
Location: kernel/trace/bpf_trace.c:701
Inline: True
```
**Symbols:**

```
ffffffff811e71d0-ffffffff811e71da: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81217de0)
Location: kernel/trace/bpf_trace.c:701
Inline: True
```
**Symbols:**

```
ffffffff81217de0-ffffffff81217dea: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255c10)
Location: kernel/trace/bpf_trace.c:753
Inline: True
```
**Symbols:**

```
ffffffff81255c10-ffffffff81255c1e: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5120)
Location: kernel/trace/bpf_trace.c:758
Inline: True
```
**Symbols:**

```
ffffffff812a5120-ffffffff812a512e: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c75d0)
Location: kernel/trace/bpf_trace.c:761
Inline: True
```
**Symbols:**

```
ffffffff812c75d0-ffffffff812c75de: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e3f90)
Location: kernel/trace/bpf_trace.c:761
Inline: True
```
**Symbols:**

```
ffffffff812e3f90-ffffffff812e3f9e: bpf_get_current_task (STB_GLOBAL)
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
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024c398)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
ffff80001024c398-ffff80001024c3a0: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c047e968)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
c047e968-c047e98c: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e7850)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
c0000000002e7850-c0000000002e7858: bpf_get_current_task (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4d10)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
ffffffff811c4d10-ffffffff811c4d1a: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b7af0)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
ffffffff811b7af0-ffffffff811b7afa: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2ae0)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
ffffffff811c2ae0-ffffffff811c2aea: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_get_current_task(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d0b80)
Location: kernel/trace/bpf_trace.c:552
Inline: False
```
**Symbols:**

```
ffffffff811d0b80-ffffffff811d0b8a: bpf_get_current_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_4</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_5</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
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
