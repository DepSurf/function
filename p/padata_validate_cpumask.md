# Function: <code>padata_validate_cpumask</code>

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
In kernel/padata.c (ffffffff8118a140)
Location: kernel/padata.c:564
Inline: True
Direct callers:
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
```
**Symbols:**

```
ffffffff8118a140-ffffffff8118a176: padata_validate_cpumask.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119d0e0)
Location: kernel/padata.c:564
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff811abe10)
Location: kernel/padata.c:561
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811abe10-ffffffff811abe47: padata_validate_cpumask.isra.7 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811b3270)
Location: kernel/padata.c:557
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811b3270-ffffffff811b32a7: padata_validate_cpumask.isra.7 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811c6ec0)
Location: kernel/padata.c:622
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811c6ec0-ffffffff811c6ef7: padata_validate_cpumask.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff811e7110)
Location: kernel/padata.c:623
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811e7110-ffffffff811e714e: padata_validate_cpumask.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff811f7e60)
Location: kernel/padata.c:623
Inline: True
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811f7e60-ffffffff811f7e9e: padata_validate_cpumask.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff8120fce0)
Location: kernel/padata.c:635
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_remove_cpu
  - kernel/padata.c:__padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8120fce0-ffffffff8120fd28: padata_validate_cpumask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff8121d300)
Location: kernel/padata.c:590
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8121d300-ffffffff8121d348: padata_validate_cpumask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812494c0)
Location: kernel/padata.c:710
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff812494c0-ffffffff8124951a: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81253a40)
Location: kernel/padata.c:679
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff81253a40-ffffffff81253a9a: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81258060)
Location: kernel/padata.c:679
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81258060-ffffffff812580ba: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81293bd0)
Location: kernel/padata.c:666
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81293bd0-ffffffff81293c2a: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812e9b80)
Location: kernel/padata.c:666
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812e9b80-ffffffff812e9bdf: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff813539d0)
Location: kernel/padata.c:679
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff813539d0-ffffffff81353a2f: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81384bd0)
Location: kernel/padata.c:679
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81384bd0-ffffffff81384c2f: padata_validate_cpumask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool padata_validate_cpumask(struct padata_instance *pinst, const struct cpumask *cpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff813adfe0)
Location: kernel/padata.c:679
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff813adfe0-ffffffff813ae03f: padata_validate_cpumask (STB_LOCAL)
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
In kernel/padata.c (ffff8000102a987c)
Location: kernel/padata.c:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d8b4c)
Location: kernel/padata.c:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035e070)
Location: kernel/padata.c:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d2c6c)
Location: kernel/padata.c:590
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff81215950)
Location: kernel/padata.c:590
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81215950-ffffffff81215998: padata_validate_cpumask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff812086b0)
Location: kernel/padata.c:590
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812086b0-ffffffff812086f8: padata_validate_cpumask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff812136f0)
Location: kernel/padata.c:590
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812136f0-ffffffff81213738: padata_validate_cpumask.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff81222cd0)
Location: kernel/padata.c:590
Inline: True
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81222cd0-ffffffff81222d18: padata_validate_cpumask.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
