# Function: <code>padata_setup_cpumasks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8118a2d5)
Location: kernel/padata.c:350
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
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
In kernel/padata.c (ffffffff8119c99a)
Location: kernel/padata.c:350
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811abec5)
Location: kernel/padata.c:347
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b3325)
Location: kernel/padata.c:343
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c6f7a)
Location: kernel/padata.c:401
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811e71ca)
Location: kernel/padata.c:402
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f7f1a)
Location: kernel/padata.c:402
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8120fda5)
Location: kernel/padata.c:414
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_pd
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
In kernel/padata.c (ffffffff8121d350)
Location: kernel/padata.c:353
Inline: True
Direct callers:
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8121d350-ffffffff8121d3b8: padata_setup_cpumasks.isra.0 (STB_LOCAL)
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
In kernel/padata.c (ffffffff81249dcb)
Location: kernel/padata.c:428
Inline: True
Inline callers:
  - kernel/padata.c:__padata_set_cpumasks
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
In kernel/padata.c (ffffffff812544ee)
Location: kernel/padata.c:424
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:__padata_set_cpumasks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int padata_setup_cpumasks(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812580c0)
Location: kernel/padata.c:424
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812580c0-ffffffff81258126: padata_setup_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int padata_setup_cpumasks(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81293c30)
Location: kernel/padata.c:411
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81293c30-ffffffff81293c96: padata_setup_cpumasks (STB_LOCAL)
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
In kernel/padata.c (ffffffff812ea94b)
Location: kernel/padata.c:411
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff81354865)
Location: kernel/padata.c:424
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff81385b9d)
Location: kernel/padata.c:424
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
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
In kernel/padata.c (ffffffff813af05c)
Location: kernel/padata.c:424
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_set_cpumask
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
int padata_setup_cpumasks(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102a8eb8)
Location: kernel/padata.c:353
Inline: False
Direct callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffff8000102a8eb8-ffff8000102a8f1c: padata_setup_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int padata_setup_cpumasks(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d8098)
Location: kernel/padata.c:353
Inline: False
Direct callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
c04d8098-c04d80f0: padata_setup_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int padata_setup_cpumasks(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035d230)
Location: kernel/padata.c:353
Inline: False
Direct callers:
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
c00000000035d230-c00000000035d2c4: padata_setup_cpumasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int padata_setup_cpumasks(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d22a0)
Location: kernel/padata.c:353
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffe0001d22a0-ffffffe0001d232e: padata_setup_cpumasks (STB_LOCAL)
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
In kernel/padata.c (ffffffff812159a0)
Location: kernel/padata.c:353
Inline: True
Direct callers:
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812159a0-ffffffff81215a08: padata_setup_cpumasks.isra.0 (STB_LOCAL)
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
In kernel/padata.c (ffffffff81208700)
Location: kernel/padata.c:353
Inline: True
Direct callers:
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81208700-ffffffff81208768: padata_setup_cpumasks.isra.0 (STB_LOCAL)
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
In kernel/padata.c (ffffffff81213740)
Location: kernel/padata.c:353
Inline: True
Direct callers:
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81213740-ffffffff812137a8: padata_setup_cpumasks.isra.0 (STB_LOCAL)
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
In kernel/padata.c (ffffffff81222d20)
Location: kernel/padata.c:353
Inline: True
Direct callers:
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81222d20-ffffffff81222d88: padata_setup_cpumasks.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
