# Function: <code>padata_set_cpumask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8118a5d0)
Location: kernel/padata.c:645
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff8118a5d0-ffffffff8118a642: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119cb50)
Location: kernel/padata.c:618
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff8119cb50-ffffffff8119cd16: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811ac570)
Location: kernel/padata.c:615
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff811ac570-ffffffff811ac6d2: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b3bb0)
Location: kernel/padata.c:611
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff811b3bb0-ffffffff811b3d0f: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c7840)
Location: kernel/padata.c:676
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff811c7840-ffffffff811c799f: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811e7a90)
Location: kernel/padata.c:677
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff811e7a90-ffffffff811e7bde: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f89e0)
Location: kernel/padata.c:677
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff811f89e0-ffffffff811f8b2e: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81210490)
Location: kernel/padata.c:689
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81210490-ffffffff812105e6: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8121dbf0)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff8121dbf0-ffffffff8121dd3c: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81249f76)
Location: kernel/padata.c:761
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81249e70-ffffffff81249ee7: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81254286)
Location: kernel/padata.c:730
Inline: True
Inline callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81254180-ffffffff812541f7: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81258640)
Location: kernel/padata.c:730
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81258640-ffffffff81258777: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81294260)
Location: kernel/padata.c:717
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81294260-ffffffff81294397: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812ea5b0)
Location: kernel/padata.c:717
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff812ea5b0-ffffffff812ea74e: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81354490)
Location: kernel/padata.c:730
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81354490-ffffffff8135462e: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:730
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff820e167c-ffffffff820e16f5: padata_set_cpumask.cold (STB_LOCAL)
ffffffff81385690-ffffffff81385952: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/padata.c (0)
Location: kernel/padata.c:730
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff821be0df-ffffffff821be158: padata_set_cpumask.cold (STB_LOCAL)
ffffffff813aeb20-ffffffff813aede2: padata_set_cpumask (STB_GLOBAL)
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
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102a93e0)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffff8000102a93e0-ffff8000102a958c: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d86dc)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
c04d86dc-c04d8830: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035d7e0)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
c00000000035d7e0-c00000000035da50: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, struct cpumask *cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d25fe)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffe0001d25fe-ffffffe0001d29cc: padata_set_cpumask (STB_GLOBAL)
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
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81216240)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81216240-ffffffff8121638c: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81208fa0)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81208fa0-ffffffff812090ec: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81213fe0)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81213fe0-ffffffff8121412c: padata_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int padata_set_cpumask(struct padata_instance *pinst, int cpumask_type, cpumask_var_t cpumask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81223220)
Location: kernel/padata.c:640
Inline: False
Direct callers:
  - kernel/padata.c:store_cpumask
```
**Symbols:**

```
ffffffff81223220-ffffffff8122336c: padata_set_cpumask (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct cpumask *cpumask</code> ➡️ <code>cpumask_var_t cpumask</code>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cpumask_var_t cpumask</code> ➡️ <code>struct cpumask *cpumask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cpumask_var_t cpumask</code> ➡️ <code>struct cpumask *cpumask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cpumask_var_t cpumask</code> ➡️ <code>struct cpumask *cpumask</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cpumask_var_t cpumask</code> ➡️ <code>struct cpumask *cpumask</code>
</li>
</ul>
</details>
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
