# Function: <code>set_rq_online</code>

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
In kernel/sched/core.c (ffffffff810a7000)
Location: kernel/sched/core.c:5483
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
ffffffff810a7000-ffffffff810a704e: set_rq_online.part.46 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810b2881)
Location: kernel/sched/core.c:5567
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:rq_attach_root
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:rq_attach_root
```
**Symbols:**

```
ffffffff810aa9f0-ffffffff810aaa43: set_rq_online.part.50 (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff810b8e74)
Location: kernel/sched/core.c:5601
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:rq_attach_root
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:rq_attach_root
```
**Symbols:**

```
ffffffff810b0ae0-ffffffff810b0b36: set_rq_online.part.52 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3a99)
Location: kernel/sched/core.c:5482
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810acfd0-ffffffff810ad026: set_rq_online.part.81 (STB_LOCAL)
ffffffff810b3a00-ffffffff810b3a1c: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810bad39)
Location: kernel/sched/core.c:5561
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810b3e80-ffffffff810b3ed9: set_rq_online.part.79 (STB_LOCAL)
ffffffff810baca0-ffffffff810bacbc: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c221a)
Location: kernel/sched/core.c:5687
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810bb270-ffffffff810bb2c9: set_rq_online.part.75 (STB_LOCAL)
ffffffff810c2100-ffffffff810c211b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb536)
Location: kernel/sched/core.c:5670
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810c4700-ffffffff810c4759: set_rq_online.part.75 (STB_LOCAL)
ffffffff810cb420-ffffffff810cb43b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3553)
Location: kernel/sched/core.c:6122
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810ca440-ffffffff810ca49d: set_rq_online.part.0 (STB_LOCAL)
ffffffff810d3490-ffffffff810d34ab: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddac3)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810d3710-ffffffff810d376d: set_rq_online.part.0 (STB_LOCAL)
ffffffff810dda00-ffffffff810dda1b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e628c)
Location: kernel/sched/core.c:6546
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810dd410-ffffffff810dd46d: set_rq_online.part.0 (STB_LOCAL)
ffffffff810e61b0-ffffffff810e61cb: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e401b)
Location: kernel/sched/core.c:7380
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810d9ce0-ffffffff810d9d4e: set_rq_online.part.0 (STB_LOCAL)
ffffffff810e3f10-ffffffff810e3f2b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5feb)
Location: kernel/sched/core.c:7749
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810db280-ffffffff810db2ee: set_rq_online.part.0 (STB_LOCAL)
ffffffff810e5ee0-ffffffff810e5efb: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810fd19b)
Location: kernel/sched/core.c:8946
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810ef120-ffffffff810ef18e: set_rq_online.part.0 (STB_LOCAL)
ffffffff810fd040-ffffffff810fd05b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81119b60)
Location: kernel/sched/core.c:9234
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff8110b940-ffffffff8110b9bc: set_rq_online.part.0 (STB_LOCAL)
ffffffff81119a10-ffffffff81119a3b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff811414b0)
Location: kernel/sched/core.c:9424
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff81131cf0-ffffffff81131d6c: set_rq_online.part.0 (STB_LOCAL)
ffffffff81141340-ffffffff8114136b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff8114d130)
Location: kernel/sched/core.c:9568
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff8113ff60-ffffffff8113ffdc: set_rq_online.part.0 (STB_LOCAL)
ffffffff8114cfc0-ffffffff8114cfeb: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff81158df0)
Location: kernel/sched/core.c:9557
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/build_utility.c:rq_attach_root
```
**Symbols:**

```
ffffffff8114aec0-ffffffff8114af3c: set_rq_online.part.0 (STB_LOCAL)
ffffffff81158c80-ffffffff81158cab: set_rq_online (STB_GLOBAL)
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
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff80001013d320)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffff8000101342d8-ffff80001013435c: set_rq_online.part.0 (STB_LOCAL)
ffff80001013d158-ffff80001013d198: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c038d3e8)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
c0382b2c-c0382b90: set_rq_online.part.0 (STB_LOCAL)
c038d2fc-c038d324: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c00000000018c048)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
c00000000017e700-c00000000017e7c4: set_rq_online.part.0 (STB_LOCAL)
c00000000018bf00-c00000000018bf20: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec704)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffe0000e5fce-ffffffe0000e603e: set_rq_online.part.0 (STB_LOCAL)
ffffffe0000ec5ac-ffffffe0000ec5e0: set_rq_online (STB_GLOBAL)
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
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7cb3)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810cda00-ffffffff810cda5d: set_rq_online.part.0 (STB_LOCAL)
ffffffff810d7bf0-ffffffff810d7c0b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c65d3)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810bc290-ffffffff810bc2ed: set_rq_online.part.0 (STB_LOCAL)
ffffffff810c6510-ffffffff810c652b: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d44a3)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810cce70-ffffffff810ccecd: set_rq_online.part.0 (STB_LOCAL)
ffffffff810d43e0-ffffffff810d43fb: set_rq_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_rq_online(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810df8b3)
Location: kernel/sched/core.c:6311
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
Direct callers:
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/topology.c:rq_attach_root
```
**Symbols:**

```
ffffffff810d5800-ffffffff810d585d: set_rq_online.part.0 (STB_LOCAL)
ffffffff810df7f0-ffffffff810df80b: set_rq_online (STB_GLOBAL)
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
