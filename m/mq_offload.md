# Function: <code>mq_offload</code>

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
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff818cddb0)
Location: net/sched/sch_mq.c:27
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff818cddb0-ffffffff818cde36: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff818f8f80)
Location: net/sched/sch_mq.c:27
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff818f8f80-ffffffff818f9006: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81958790)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81958790-ffffffff81958817: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff8198ec30)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff8198ec30-ffffffff8198ecb7: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81a66f60)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81a66f60-ffffffff81a66fd9: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81a6ef10)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81a6ef10-ffffffff81a6ef8e: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81a577d0)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81a577d0-ffffffff81a5784e: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81b10740)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81b10740-ffffffff81b107be: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81c97a20)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81c97a20-ffffffff81c97ab2: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81e53910)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81e53910-ffffffff81e539a2: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81eaf190)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81eaf190-ffffffff81eaf222: mq_offload.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_mq.c (ffffffff81f71c30)
Location: net/sched/sch_mq.c:24
Inline: True
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff81f71c30-ffffffff81f71cbf: mq_offload.isra.0 (STB_LOCAL)
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
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffff800010c3a960)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffff800010c3a960-ffff800010c3a9f4: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (c0d4c7d8)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
c0d4c7d8-c0d4c880: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (c000000000d33740)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
c000000000d33740-c000000000d33808: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffe0007ab6ee)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffe0007ab6ee-ffffffe0007ab74a: mq_offload (STB_LOCAL)
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
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff8192eaa0)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff8192eaa0-ffffffff8192eb27: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff818e85a0)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff818e85a0-ffffffff818e8627: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff8197fc30)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff8197fc30-ffffffff8197fcb7: mq_offload (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mq_offload(struct Qdisc *sch, enum tc_mq_command cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_mq.c (ffffffff819a2190)
Location: net/sched/sch_mq.c:24
Inline: False
Direct callers:
  - net/sched/sch_mq.c:mq_init
  - net/sched/sch_mq.c:mq_destroy
```
**Symbols:**

```
ffffffff819a2190-ffffffff819a2217: mq_offload (STB_LOCAL)
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
