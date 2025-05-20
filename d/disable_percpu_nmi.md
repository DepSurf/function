# Function: <code>disable_percpu_nmi</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d320)
Location: kernel/irq/manage.c:2281
Inline: False
```
**Symbols:**

```
ffffffff8110d320-ffffffff8110d330: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81119710)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffffffff81119710-ffffffff81119720: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81124fd0)
Location: kernel/irq/manage.c:2312
Inline: False
```
**Symbols:**

```
ffffffff81124fd0-ffffffff81124fe0: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81120e30)
Location: kernel/irq/manage.c:2382
Inline: False
```
**Symbols:**

```
ffffffff81120e30-ffffffff81120e40: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81121110)
Location: kernel/irq/manage.c:2389
Inline: False
```
**Symbols:**

```
ffffffff81121110-ffffffff81121120: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81141690)
Location: kernel/irq/manage.c:2418
Inline: False
```
**Symbols:**

```
ffffffff81141690-ffffffff811416a0: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811650b0)
Location: kernel/irq/manage.c:2452
Inline: False
```
**Symbols:**

```
ffffffff811650b0-ffffffff811650c6: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81198f20)
Location: kernel/irq/manage.c:2444
Inline: False
```
**Symbols:**

```
ffffffff81198f20-ffffffff81198f36: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811aac00)
Location: kernel/irq/manage.c:2450
Inline: False
```
**Symbols:**

```
ffffffff811aac00-ffffffff811aac16: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811ba810)
Location: kernel/irq/manage.c:2447
Inline: False
```
**Symbols:**

```
ffffffff811ba810-ffffffff811ba826: disable_percpu_nmi (STB_GLOBAL)
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
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017c390)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffff80001017c390-ffff80001017c3bc: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cd334)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
c03cd334-c03cd350: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d6f30)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
c0000000001d6f30-c0000000001d6f44: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000115a70)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffffffe000115a70-ffffffe000115a9a: disable_percpu_nmi (STB_GLOBAL)
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
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81111cf0)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffffffff81111cf0-ffffffff81111d00: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102a20)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffffffff81102a20-ffffffff81102a30: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110fbe0)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffffffff8110fbe0-ffffffff8110fbf0: disable_percpu_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void disable_percpu_nmi(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111b110)
Location: kernel/irq/manage.c:2273
Inline: False
```
**Symbols:**

```
ffffffff8111b110-ffffffff8111b120: disable_percpu_nmi (STB_GLOBAL)
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
