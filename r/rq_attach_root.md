# Function: <code>rq_attach_root</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a81c0)
Location: kernel/sched/core.c:5833
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810a81c0-ffffffff810a82b4: rq_attach_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aad80)
Location: kernel/sched/core.c:5794
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810aad80-ffffffff810aae6f: rq_attach_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b1010)
Location: kernel/sched/core.c:5832
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810b1010-ffffffff810b1108: rq_attach_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cb320)
Location: kernel/sched/topology.c:225
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810cb320-ffffffff810cb3e4: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d2ad0)
Location: kernel/sched/topology.c:225
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810d2ad0-ffffffff810d2b94: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dab20)
Location: kernel/sched/topology.c:217
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810dab20-ffffffff810dabe4: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e4670)
Location: kernel/sched/topology.c:411
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810e4670-ffffffff810e4734: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eb630)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810eb630-ffffffff810eb6f8: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f6fd0)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f6fd0-ffffffff810f7098: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101a10)
Location: kernel/sched/topology.c:438
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81101a10-ffffffff81101adb: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811005b0)
Location: kernel/sched/topology.c:465
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff811005b0-ffffffff8110067b: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81102750)
Location: kernel/sched/topology.c:465
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81102750-ffffffff8110281b: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111f2b0)
Location: kernel/sched/topology.c:465
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff8111f2b0-ffffffff8111f39e: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811492c0)
Location: kernel/sched/topology.c:485
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff811492c0-ffffffff811493a3: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177bd0)
Location: kernel/sched/topology.c:485
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff81177bd0-ffffffff81177cb2: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:487
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff820d69da-ffffffff820d69ef: rq_attach_root.cold (STB_LOCAL)
ffffffff81188810-ffffffff81188946: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/topology.c:489
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/build_utility.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff821b1c70-ffffffff821b1c85: rq_attach_root.cold (STB_LOCAL)
ffffffff811970f0-ffffffff81197226: rq_attach_root (STB_GLOBAL)
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
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015b1f8)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffff80001015b1f8-ffff80001015b3d4: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a7cdc)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c03a7cdc-c03a7e0c: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001af740)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c0000000001af740-c0000000001af938: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe0001005a2)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffe0001005a2-ffffffe0001006ea: rq_attach_root (STB_GLOBAL)
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
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f03d0)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f03d0-ffffffff810f0498: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e0440)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810e0440-ffffffff810e0508: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ed500)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810ed500-ffffffff810ed5c8: rq_attach_root (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rq_attach_root(struct rq *rq, struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8540)
Location: kernel/sched/topology.c:440
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f8540-ffffffff810f8608: rq_attach_root (STB_GLOBAL)
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
