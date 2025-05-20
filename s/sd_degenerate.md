# Function: <code>sd_degenerate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a58a0)
Location: kernel/sched/core.c:5766
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810a58a0-ffffffff810a58e7: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9ee0)
Location: kernel/sched/core.c:5727
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810a9ee0-ffffffff810a9f27: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afe10)
Location: kernel/sched/core.c:5763
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_attach_domain
  - kernel/sched/core.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810afe10-ffffffff810afe5a: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cb2d0)
Location: kernel/sched/topology.c:156
Inline: True
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810cb2d0-ffffffff810cb318: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d2a80)
Location: kernel/sched/topology.c:156
Inline: True
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810d2a80-ffffffff810d2ac8: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810daad0)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810daad0-ffffffff810dab18: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e4620)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810e4620-ffffffff810e4668: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810eb5e0)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810eb5e0-ffffffff810eb628: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f6f80)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f6f80-ffffffff810f6fc8: sd_degenerate (STB_LOCAL)
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
In kernel/sched/topology.c (ffffffff81101b3e)
Location: kernel/sched/topology.c:140
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff811006de)
Location: kernel/sched/topology.c:170
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff8110287e)
Location: kernel/sched/topology.c:170
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/topology.c (ffffffff8111f40c)
Location: kernel/sched/topology.c:170
Inline: True
Inline callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
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
In kernel/sched/build_utility.c (ffffffff8114941f)
Location: kernel/sched/topology.c:169
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
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
In kernel/sched/build_utility.c (ffffffff81177d3f)
Location: kernel/sched/topology.c:169
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
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
In kernel/sched/build_utility.c (ffffffff811889cf)
Location: kernel/sched/topology.c:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
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
In kernel/sched/build_utility.c (ffffffff811972af)
Location: kernel/sched/topology.c:171
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:cpu_attach_domain
  - kernel/sched/build_utility.c:cpu_attach_domain
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
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015aad0)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffff80001015aad0-ffff80001015ab40: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a791c)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c03a791c-c03a7980: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001aee70)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
c0000000001aee70-c0000000001aef08: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe00010053c)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffe00010053c-ffffffe0001005a2: sd_degenerate (STB_LOCAL)
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
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f0380)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f0380-ffffffff810f03c8: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e03f0)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810e03f0-ffffffff810e0438: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ed4b0)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810ed4b0-ffffffff810ed4f8: sd_degenerate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sd_degenerate(struct sched_domain *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f84f0)
Location: kernel/sched/topology.c:148
Inline: False
Direct callers:
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
  - kernel/sched/topology.c:cpu_attach_domain
```
**Symbols:**

```
ffffffff810f84f0-ffffffff810f8538: sd_degenerate (STB_LOCAL)
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
