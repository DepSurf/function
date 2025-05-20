# Function: <code>has_cpu_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e7060)
Location: mm/slub.c:2165
Inline: False
```
**Symbols:**

```
ffffffff811e7060-ffffffff811e7092: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206130)
Location: mm/slub.c:2294
Inline: False
```
**Symbols:**

```
ffffffff81206130-ffffffff81206162: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218150)
Location: mm/slub.c:2297
Inline: False
```
**Symbols:**

```
ffffffff81218150-ffffffff81218182: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81223cd0)
Location: mm/slub.c:2301
Inline: False
```
**Symbols:**

```
ffffffff81223cd0-ffffffff81223d02: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f320)
Location: mm/slub.c:2314
Inline: False
```
**Symbols:**

```
ffffffff8123f320-ffffffff8123f352: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81262bc0)
Location: mm/slub.c:2295
Inline: False
```
**Symbols:**

```
ffffffff81262bc0-ffffffff81262bf2: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81277440)
Location: mm/slub.c:2345
Inline: False
```
**Symbols:**

```
ffffffff81277440-ffffffff81277472: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81292d80)
Location: mm/slub.c:2352
Inline: False
```
**Symbols:**

```
ffffffff81292d80-ffffffff81292db7: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a2b00)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffffffff812a2b00-ffffffff812a2b37: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812d72a0)
Location: mm/slub.c:2389
Inline: False
```
**Symbols:**

```
ffffffff812d72a0-ffffffff812d72d7: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e2dc0)
Location: mm/slub.c:2454
Inline: False
```
**Symbols:**

```
ffffffff812e2dc0-ffffffff812e2df7: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ea540)
Location: mm/slub.c:2471
Inline: False
```
**Symbols:**

```
ffffffff812ea540-ffffffff812ea577: has_cpu_slab (STB_LOCAL)
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
In mm/slub.c (ffffffff81333143)
Location: mm/slub.c:2664
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
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
In mm/slub.c (ffffffff813a49b2)
Location: mm/slub.c:2706
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
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
In mm/slub.c (ffffffff8142527f)
Location: mm/slub.c:2795
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
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
In mm/slub.c (ffffffff8145a62f)
Location: mm/slub.c:2805
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
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
In mm/slub.c (ffffffff814556ff)
Location: mm/slub.c:3079
Inline: True
Inline callers:
  - mm/slub.c:flush_all_cpus_locked
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
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010342be0)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffff800010342be0-ffff800010342c40: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c05482a4)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
c05482a4-c05482f0: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000420100)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
c000000000420100-c000000000420150: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000236832)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffffffe000236832-ffffffe000236884: has_cpu_slab (STB_LOCAL)
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
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129b0e0)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffffffff8129b0e0-ffffffff8129b117: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8128cca0)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffffffff8128cca0-ffffffff8128ccd7: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81298ef0)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffffffff81298ef0-ffffffff81298f27: has_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool has_cpu_slab(int cpu, void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a8d10)
Location: mm/slub.c:2331
Inline: False
```
**Symbols:**

```
ffffffff812a8d10-ffffffff812a8d47: has_cpu_slab (STB_LOCAL)
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
