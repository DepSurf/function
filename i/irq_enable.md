# Function: <code>irq_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810de1a0)
Location: kernel/irq/chip.c:222
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff810de1a0-ffffffff810de1e7: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e3af0)
Location: kernel/irq/chip.c:222
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff810e3af0-ffffffff810e3b37: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea340)
Location: kernel/irq/chip.c:221
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff810ea340-ffffffff810ea387: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9980)
Location: kernel/irq/chip.c:305
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff810e9980-ffffffff810e99de: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1e50)
Location: kernel/irq/chip.c:328
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff810f1e50-ffffffff810f1eb1: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa290)
Location: kernel/irq/chip.c:326
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff810fa290-ffffffff810fa2ec: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105a50)
Location: kernel/irq/chip.c:326
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff81105a50-ffffffff81105aac: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110ef10)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff8110ef10-ffffffff8110ef70: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b1d0)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff8111b1d0-ffffffff8111b230: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127380)
Location: kernel/irq/chip.c:332
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff81127380-ffffffff811273f5: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122f80)
Location: kernel/irq/chip.c:332
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff81122f80-ffffffff81122ff5: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123280)
Location: kernel/irq/chip.c:335
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff81123280-ffffffff811232f5: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143850)
Location: kernel/irq/chip.c:335
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff81143850-ffffffff811438c5: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167610)
Location: kernel/irq/chip.c:332
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff81167610-ffffffff8116768f: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119b9c0)
Location: kernel/irq/chip.c:334
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff8119b9c0-ffffffff8119ba3f: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ad810)
Location: kernel/irq/chip.c:335
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff811ad810-ffffffff811ad88f: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bd410)
Location: kernel/irq/chip.c:335
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff811bd410-ffffffff811bd48f: irq_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f120)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffff80001017f120-ffff80001017f19c: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf310)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
c03cf310-c03cf388: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9a20)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
c0000000001d9a20-c0000000001d9ad0: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001176fa)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffe0001176fa-ffffffe000117766: irq_enable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811137b0)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff811137b0-ffffffff81113810: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811044c0)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff811044c0-ffffffff81104520: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811116a0)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff811116a0-ffffffff81111700: irq_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_enable(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111cc60)
Location: kernel/irq/chip.c:332
Inline: True
Direct callers:
  - kernel/irq/chip.c:irq_startup
  - kernel/irq/chip.c:__irq_startup
```
**Symbols:**

```
ffffffff8111cc60-ffffffff8111ccc0: irq_enable (STB_GLOBAL)
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
