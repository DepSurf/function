# Function: <code>set_rq_offline</code>

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
In kernel/sched/core.c (ffffffff810a6930)
Location: kernel/sched/core.c:5498
Inline: True
Inline callers:
  - kernel/sched/core.c:rq_attach_root
  - kernel/sched/core.c:migration_call
Direct callers:
  - kernel/sched/core.c:rq_attach_root
  - kernel/sched/core.c:migration_call
```
**Symbols:**

```
ffffffff810a6930-ffffffff810a6983: set_rq_offline.part.47 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810b2bd7)
Location: kernel/sched/core.c:5582
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:rq_attach_root
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:rq_attach_root
```
**Symbols:**

```
ffffffff810aa990-ffffffff810aa9e8: set_rq_offline.part.51 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810b91ba)
Location: kernel/sched/core.c:5616
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:rq_attach_root
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:rq_attach_root
```
**Symbols:**

```
ffffffff810b0a80-ffffffff810b0adb: set_rq_offline.part.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3cc0)
Location: kernel/sched/core.c:5497
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810acbb0-ffffffff810acc0b: set_rq_offline.part.82 (STB_LOCAL)
ffffffff810b3a20-ffffffff810b3a3c: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810baf5d)
Location: kernel/sched/core.c:5576
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810b3e00-ffffffff810b3e5e: set_rq_offline.part.80 (STB_LOCAL)
ffffffff810bacc0-ffffffff810bacdc: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2120)
Location: kernel/sched/core.c:5702
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810c2120-ffffffff810c2189: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb440)
Location: kernel/sched/core.c:5685
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810cb440-ffffffff810cb4a9: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d373b)
Location: kernel/sched/core.c:6137
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810ca0a0-ffffffff810ca101: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810d34b0-ffffffff810d34cb: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddcaf)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810d3500-ffffffff810d3564: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810dda20-ffffffff810dda3b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6455)
Location: kernel/sched/core.c:6561
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810dd320-ffffffff810dd384: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810e61d0-ffffffff810e61eb: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4190)
Location: kernel/sched/core.c:7395
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810d9be0-ffffffff810d9c53: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810e3f30-ffffffff810e3f4b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6168)
Location: kernel/sched/core.c:7764
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810db200-ffffffff810db273: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810e5f00-ffffffff810e5f1b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810fd457)
Location: kernel/sched/core.c:8961
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810ef020-ffffffff810ef096: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810fd060-ffffffff810fd07b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81119d28)
Location: kernel/sched/core.c:9249
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff8110b9c0-ffffffff8110ba39: set_rq_offline.part.0 (STB_LOCAL)
ffffffff81119a40-ffffffff81119a6b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81141674)
Location: kernel/sched/core.c:9439
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff81131d80-ffffffff81131df9: set_rq_offline.part.0 (STB_LOCAL)
ffffffff81141380-ffffffff811413ab: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff8114d307)
Location: kernel/sched/core.c:9583
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff81146c70-ffffffff81146cee: set_rq_offline.part.0 (STB_LOCAL)
ffffffff8114d000-ffffffff8114d02b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81158fc7)
Location: kernel/sched/core.c:9572
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff811524a0-ffffffff8115251e: set_rq_offline.part.0 (STB_LOCAL)
ffffffff81158cc0-ffffffff81158ceb: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff80001013d5c8)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffff800010134248-ffff8000101342d4: set_rq_offline.part.0 (STB_LOCAL)
ffff80001013d198-ffff80001013d1cc: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c038d604)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
c0382b90-c0382bf4: set_rq_offline.part.0 (STB_LOCAL)
c038d324-c038d34c: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c00000000018c42c)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
c00000000017e7d0-c00000000017e89c: set_rq_offline.part.0 (STB_LOCAL)
c00000000018bf20-c00000000018bf40: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec5e0)
Location: kernel/sched/core.c:6326
Inline: False
Direct callers:
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffe0000ec5e0-ffffffe0000ec65e: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7e9f)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810cd800-ffffffff810cd864: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810d7c10-ffffffff810d7c2b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c686f)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810bc080-ffffffff810bc0e4: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810c6530-ffffffff810c654b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d468f)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810ccc60-ffffffff810cccc1: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810d4400-ffffffff810d441b: set_rq_offline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_offline(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfa9a)
Location: kernel/sched/core.c:6326
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810d56a0-ffffffff810d5704: set_rq_offline.part.0 (STB_LOCAL)
ffffffff810df810-ffffffff810df82b: set_rq_offline (STB_GLOBAL)
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
