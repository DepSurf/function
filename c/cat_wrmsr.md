# Function: <code>cat_wrmsr</code>

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
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81041060)
Location: arch/x86/kernel/cpu/intel_rdt.c:317
Inline: False
```
**Symbols:**

```
ffffffff81041060-ffffffff810410c5: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff810448b0)
Location: arch/x86/kernel/cpu/intel_rdt.c:318
Inline: False
```
**Symbols:**

```
ffffffff810448b0-ffffffff81044915: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046b50)
Location: arch/x86/kernel/cpu/intel_rdt.c:372
Inline: False
```
**Symbols:**

```
ffffffff81046b50-ffffffff81046bb5: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055b50)
Location: arch/x86/kernel/cpu/resctrl/core.c:405
Inline: False
```
**Symbols:**

```
ffffffff81055b50-ffffffff81055bb5: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81058dc0)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff81058dc0-ffffffff81058e22: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059690)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff81059690-ffffffff810596f2: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105e8b0)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff8105e8b0-ffffffff8105e912: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105cdd0)
Location: arch/x86/kernel/cpu/resctrl/core.c:399
Inline: False
```
**Symbols:**

```
ffffffff8105cdd0-ffffffff8105ce32: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d730)
Location: arch/x86/kernel/cpu/resctrl/core.c:399
Inline: False
```
**Symbols:**

```
ffffffff8105d730-ffffffff8105d792: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81066de0)
Location: arch/x86/kernel/cpu/resctrl/core.c:326
Inline: False
```
**Symbols:**

```
ffffffff81066de0-ffffffff81066e39: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073650)
Location: arch/x86/kernel/cpu/resctrl/core.c:326
Inline: False
```
**Symbols:**

```
ffffffff81073650-ffffffff810736c2: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81083950)
Location: arch/x86/kernel/cpu/resctrl/core.c:316
Inline: False
```
**Symbols:**

```
ffffffff81083950-ffffffff810839c2: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81085e00)
Location: arch/x86/kernel/cpu/resctrl/core.c:341
Inline: False
```
**Symbols:**

```
ffffffff81085e00-ffffffff81085e7b: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108cdc0)
Location: arch/x86/kernel/cpu/resctrl/core.c:345
Inline: False
```
**Symbols:**

```
ffffffff8108cdc0-ffffffff8108ce3b: cat_wrmsr (STB_LOCAL)
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
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059210)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff81059210-ffffffff81059272: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810493a0)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff810493a0-ffffffff8104940e: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059640)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff81059640-ffffffff810596a2: cat_wrmsr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cat_wrmsr(struct rdt_domain *d, struct msr_param *m, struct rdt_resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105aae0)
Location: arch/x86/kernel/cpu/resctrl/core.c:397
Inline: False
```
**Symbols:**

```
ffffffff8105aae0-ffffffff8105ab42: cat_wrmsr (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
