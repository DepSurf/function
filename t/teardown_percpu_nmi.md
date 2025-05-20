# Function: <code>teardown_percpu_nmi</code>

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
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:2606
Inline: False
```
**Symbols:**

```
ffffffff8110d941-ffffffff8110d954: teardown_percpu_nmi.cold (STB_LOCAL)
ffffffff8110d620-ffffffff8110d6a4: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119a10)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffffffff81119a10-ffffffff81119a94: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811252e0)
Location: kernel/irq/manage.c:2637
Inline: False
```
**Symbols:**

```
ffffffff811252e0-ffffffff81125362: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121140)
Location: kernel/irq/manage.c:2707
Inline: False
```
**Symbols:**

```
ffffffff81121140-ffffffff811211c2: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121420)
Location: kernel/irq/manage.c:2714
Inline: False
```
**Symbols:**

```
ffffffff81121420-ffffffff811214a2: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811419a0)
Location: kernel/irq/manage.c:2743
Inline: False
```
**Symbols:**

```
ffffffff811419a0-ffffffff81141a22: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81165430)
Location: kernel/irq/manage.c:2777
Inline: False
```
**Symbols:**

```
ffffffff81165430-ffffffff811654e3: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81199320)
Location: kernel/irq/manage.c:2769
Inline: False
```
**Symbols:**

```
ffffffff81199320-ffffffff811993dc: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ab000)
Location: kernel/irq/manage.c:2775
Inline: False
```
**Symbols:**

```
ffffffff811ab000-ffffffff811ab0bc: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811bac40)
Location: kernel/irq/manage.c:2772
Inline: False
```
**Symbols:**

```
ffffffff811bac40-ffffffff811bacfc: teardown_percpu_nmi (STB_GLOBAL)
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
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c7d0)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffff80001017c7d0-ffff80001017c868: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cd69c)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
c03cd69c-c03cd750: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d7480)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
c0000000001d7480-c0000000001d7550: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000115d86)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffffffe000115d86-ffffffe000115de8: teardown_percpu_nmi (STB_GLOBAL)
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
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81111ff0)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffffffff81111ff0-ffffffff81112074: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102d20)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffffffff81102d20-ffffffff81102da4: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110fee0)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffffffff8110fee0-ffffffff8110ff64: teardown_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void teardown_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111b430)
Location: kernel/irq/manage.c:2598
Inline: False
```
**Symbols:**

```
ffffffff8111b430-ffffffff8111b4d2: teardown_percpu_nmi (STB_GLOBAL)
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
