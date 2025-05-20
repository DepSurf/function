# Function: <code>rdt_get_cache_alloc_cfg</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810419ff)
Location: arch/x86/kernel/cpu/intel_rdt.c:246
Inline: False
```
**Symbols:**

```
ffffffff810419ff-ffffffff81041a94: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81044e4f)
Location: arch/x86/kernel/cpu/intel_rdt.c:246
Inline: False
```
**Symbols:**

```
ffffffff81044e4f-ffffffff81044ee4: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810471aa)
Location: arch/x86/kernel/cpu/intel_rdt.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
**Symbols:**

```
ffffffff810471aa-ffffffff8104723f: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810561ca)
Location: arch/x86/kernel/cpu/resctrl/core.c:311
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff810561ca-ffffffff8105625f: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105939a)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff8105939a-ffffffff8105942f: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059c6a)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff81059c6a-ffffffff81059cff: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105f10c)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff8105f10c-ffffffff8105f19f: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81bd627c)
Location: arch/x86/kernel/cpu/resctrl/core.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff81bd627c-ffffffff81bd630f: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81bc8620)
Location: arch/x86/kernel/cpu/resctrl/core.c:318
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff81bc8620-ffffffff81bc86b3: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81c9c518)
Location: arch/x86/kernel/cpu/resctrl/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff81c9c518-ffffffff81c9c5ae: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81e4b84e)
Location: arch/x86/kernel/cpu/resctrl/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff81e4b84e-ffffffff81e4b8fa: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083ad0)
Location: arch/x86/kernel/cpu/resctrl/core.c:241
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
```
**Symbols:**

```
ffffffff81083ad0-ffffffff81083b8d: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086070)
Location: arch/x86/kernel/cpu/resctrl/core.c:266
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff81086070-ffffffff8108612d: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108cf30)
Location: arch/x86/kernel/cpu/resctrl/core.c:267
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff8108cf30-ffffffff8108d003: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810597ea)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff810597ea-ffffffff8105987f: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898e7f)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059c1a)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff81059c1a-ffffffff81059caf: rdt_get_cache_alloc_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rdt_get_cache_alloc_cfg(int idx, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105b0ba)
Location: arch/x86/kernel/cpu/resctrl/core.c:303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff8105b0ba-ffffffff8105b14f: rdt_get_cache_alloc_cfg (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
