# Function: <code>oom_kill_process</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, struct task_struct *p, unsigned int points, long unsigned int totalpages, struct mem_cgroup *memcg, const char *message);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190bd0)
Location: mm/oom_kill.c:509
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
**Symbols:**

```
ffffffff81190bd0-ffffffff81190f8b: oom_kill_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, struct task_struct *p, unsigned int points, long unsigned int totalpages, const char *message);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a53c0)
Location: mm/oom_kill.c:813
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
**Symbols:**

```
ffffffff811a53c0-ffffffff811a579c: oom_kill_process (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b5530)
Location: mm/oom_kill.c:807
Inline: False
```
**Symbols:**

```
ffffffff811b5530-ffffffff811b5903: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd240)
Location: mm/oom_kill.c:812
Inline: False
```
**Symbols:**

```
ffffffff811bd240-ffffffff811bd64a: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1e50)
Location: mm/oom_kill.c:836
Inline: False
```
**Symbols:**

```
ffffffff811d1e50-ffffffff811d2282: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:838
Inline: False
```
**Symbols:**

```
ffffffff811f2c50-ffffffff811f2d12: oom_kill_process (STB_LOCAL)
ffffffff811f3b73-ffffffff811f3ef9: oom_kill_process.cold.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:938
Inline: False
```
**Symbols:**

```
ffffffff81204c70-ffffffff81204d1d: oom_kill_process (STB_LOCAL)
ffffffff81205cbd-ffffffff81205e93: oom_kill_process.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:950
Inline: False
```
**Symbols:**

```
ffffffff8121c2c0-ffffffff8121c3c8: oom_kill_process (STB_LOCAL)
ffffffff8121d1eb-ffffffff8121d1fb: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffffffff81229c90-ffffffff81229d98: oom_kill_process (STB_LOCAL)
ffffffff8122abc8-ffffffff8122abd8: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:953
Inline: False
```
**Symbols:**

```
ffffffff81256b00-ffffffff81256c3d: oom_kill_process (STB_LOCAL)
ffffffff81257986-ffffffff81257996: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:957
Inline: False
```
**Symbols:**

```
ffffffff81261710-ffffffff81261859: oom_kill_process (STB_LOCAL)
ffffffff81be6cf9-ffffffff81be6d09: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:956
Inline: False
```
**Symbols:**

```
ffffffff81265f40-ffffffff8126606c: oom_kill_process (STB_LOCAL)
ffffffff81bd8a92-ffffffff81bd8aa2: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:957
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff812a2760-ffffffff812a288c: oom_kill_process (STB_LOCAL)
ffffffff81cba371-ffffffff81cba381: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:1014
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff812fa390-ffffffff812fa537: oom_kill_process (STB_LOCAL)
ffffffff81e6ba7b-ffffffff81e6ba8b: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81364b00)
Location: mm/oom_kill.c:1013
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff81364b00-ffffffff81364cb7: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81396fc0)
Location: mm/oom_kill.c:1013
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff81396fc0-ffffffff81397177: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0d30)
Location: mm/oom_kill.c:1009
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff813c0d30-ffffffff813c0fab: oom_kill_process (STB_LOCAL)
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
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b7b00)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffff8000102b7b00-ffff8000102b7cd8: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e4740)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
c04e4740-c04e48b8: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036f910)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
c00000000036f910-c00000000036fb70: oom_kill_process (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dbd5c)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffffffe0001dbd5c-ffffffe0001dbf36: oom_kill_process (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffffffff812222e0-ffffffff812223e8: oom_kill_process (STB_LOCAL)
ffffffff81223218-ffffffff81223228: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffffffff81215490-ffffffff81215598: oom_kill_process (STB_LOCAL)
ffffffff812163c8-ffffffff812163d8: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffffffff81220080-ffffffff81220188: oom_kill_process (STB_LOCAL)
ffffffff81220fb8-ffffffff81220fc8: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void oom_kill_process(struct oom_control *oc, const char *message);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:951
Inline: False
```
**Symbols:**

```
ffffffff8122f190-ffffffff8122f2a2: oom_kill_process (STB_LOCAL)
ffffffff8123016d-ffffffff8123017d: oom_kill_process.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct mem_cgroup *memcg</code>
</li>
<li>
<b>Param reordered. </b>
<code>oc, p, points, totalpages, memcg, message</code> ➡️ <code>oc, p, points, totalpages, message</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int points</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int totalpages</code>
</li>
<li>
<b>Param reordered. </b>
<code>oc, p, points, totalpages, message</code> ➡️ <code>oc, message</code>
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
