# Function: <code>prepare_percpu_nmi</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2563
Inline: False
```
**Symbols:**

```
ffffffff8110d927-ffffffff8110d941: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff8110d560-ffffffff8110d61d: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffffffff81119c04-ffffffff81119c1e: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81119950-ffffffff81119a0d: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2594
Inline: False
```
**Symbols:**

```
ffffffff81125b32-ffffffff81125b4c: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81125220-ffffffff811252dd: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2664
Inline: False
```
**Symbols:**

```
ffffffff81be186a-ffffffff81be1884: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81121080-ffffffff8112113d: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2671
Inline: False
```
**Symbols:**

```
ffffffff81bd3925-ffffffff81bd393f: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81121360-ffffffff8112141d: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2700
Inline: False
```
**Symbols:**

```
ffffffff81cad86d-ffffffff81cad887: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff811418e0-ffffffff8114199d: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2734
Inline: False
```
**Symbols:**

```
ffffffff81e5dd3e-ffffffff81e5dd58: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81165340-ffffffff81165430: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81199200)
Location: kernel/irq/manage.c:2726
Inline: False
```
**Symbols:**

```
ffffffff81199200-ffffffff81199302: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811aaee0)
Location: kernel/irq/manage.c:2732
Inline: False
```
**Symbols:**

```
ffffffff811aaee0-ffffffff811aafe2: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bab20)
Location: kernel/irq/manage.c:2729
Inline: False
```
**Symbols:**

```
ffffffff811bab20-ffffffff811bac22: prepare_percpu_nmi (STB_GLOBAL)
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
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c6f0)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffff80001017c6f0-ffff80001017c7d0: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cd5a8)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
c03cd5a8-c03cd69c: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d7350)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
c0000000001d7350-c0000000001d7478: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000115ce8)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffffffe000115ce8-ffffffe000115d86: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffffffff811121e4-ffffffff811121fe: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81111f30-ffffffff81111fed: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffffffff81102f14-ffffffff81102f2e: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff81102c60-ffffffff81102d1d: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffffffff811100d4-ffffffff811100ee: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff8110fe20-ffffffff8110fedd: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int prepare_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2555
Inline: False
```
**Symbols:**

```
ffffffff8111b644-ffffffff8111b65e: prepare_percpu_nmi.cold (STB_LOCAL)
ffffffff8111b350-ffffffff8111b42e: prepare_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
