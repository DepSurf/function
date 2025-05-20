# Function: <code>tcf_node_bind</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff8187cea0)
Location: net/sched/sch_api.c:1650
Inline: True
```
**Symbols:**

```
ffffffff8187cea0-ffffffff8187cf7b: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818cfa40)
Location: net/sched/sch_api.c:1788
Inline: False
```
**Symbols:**

```
ffffffff818cfa40-ffffffff818cfb4f: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818fb710)
Location: net/sched/sch_api.c:1885
Inline: False
```
**Symbols:**

```
ffffffff818fb710-ffffffff818fb81f: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff8195a6d6)
Location: net/sched/sch_api.c:1898
Inline: True
```
**Symbols:**

```
ffffffff8195a6b0-ffffffff8195a7b5: tcf_node_bind (STB_LOCAL)
ffffffff8195cf18-ffffffff8195cf2b: tcf_node_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81990b50)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffffffff81990b50-ffffffff81990c6d: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a68680)
Location: net/sched/sch_api.c:1909
Inline: False
```
**Symbols:**

```
ffffffff81a68680-ffffffff81a6879d: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a70d90)
Location: net/sched/sch_api.c:1910
Inline: False
```
**Symbols:**

```
ffffffff81a70d90-ffffffff81a70ead: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81a596e0)
Location: net/sched/sch_api.c:1911
Inline: False
```
**Symbols:**

```
ffffffff81a596e0-ffffffff81a59832: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1912
Inline: False
```
**Symbols:**

```
ffffffff81b12790-ffffffff81b128f8: tcf_node_bind (STB_LOCAL)
ffffffff81d38f3e-ffffffff81d38f6e: tcf_node_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (0)
Location: net/sched/sch_api.c:1903
Inline: False
```
**Symbols:**

```
ffffffff81c9aad0-ffffffff81c9ac56: tcf_node_bind (STB_LOCAL)
ffffffff81f057f4-ffffffff81f05824: tcf_node_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81e56f7a)
Location: net/sched/sch_api.c:1921
Inline: True
```
**Symbols:**

```
ffffffff81e56f40-ffffffff81e570ca: tcf_node_bind (STB_LOCAL)
ffffffff820ad6c4-ffffffff820ad6f4: tcf_node_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81eb167a)
Location: net/sched/sch_api.c:1995
Inline: True
```
**Symbols:**

```
ffffffff81eb1640-ffffffff81eb17ca: tcf_node_bind (STB_LOCAL)
ffffffff8212e855-ffffffff8212e885: tcf_node_bind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/sched/sch_api.c (ffffffff81f7412a)
Location: net/sched/sch_api.c:2052
Inline: True
```
**Symbols:**

```
ffffffff81f740f0-ffffffff81f7427a: tcf_node_bind (STB_LOCAL)
ffffffff822105f3-ffffffff82210623: tcf_node_bind.cold (STB_LOCAL)
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
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffff800010c3d038)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffff800010c3d038-ffff800010c3d1c4: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c0d4eb40)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
c0d4eb40-c0d4ec90: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (c000000000d36800)
Location: net/sched/sch_api.c:1899
Inline: True
```
**Symbols:**

```
c000000000d36800-c000000000d369a0: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffe0007ad5cc)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffffffe0007ad5cc-ffffffe0007ad6d0: tcf_node_bind (STB_LOCAL)
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
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819309c0)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffffffff819309c0-ffffffff81930add: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff818ea4c0)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffffffff818ea4c0-ffffffff818ea5dd: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff81981b50)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffffffff81981b50-ffffffff81981c6d: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcf_node_bind(struct tcf_proto *tp, void *n, struct tcf_walker *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/sch_api.c (ffffffff819a40b0)
Location: net/sched/sch_api.c:1899
Inline: False
```
**Symbols:**

```
ffffffff819a40b0-ffffffff819a41cd: tcf_node_bind (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
