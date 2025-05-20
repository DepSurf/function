# Function: <code>register_irq_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/proc.c (ffffffff810e1d70)
Location: kernel/irq/proc.c:325
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff810e1d70-ffffffff810e1ec0: register_irq_proc.part.9 (STB_LOCAL)
ffffffff810e2090-ffffffff810e20b5: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/proc.c (ffffffff810e7ca9)
Location: kernel/irq/proc.c:324
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff810e7810-ffffffff810e7952: register_irq_proc.part.9 (STB_LOCAL)
ffffffff810e7b20-ffffffff810e7b45: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/proc.c (ffffffff810ee6e9)
Location: kernel/irq/proc.c:324
Inline: True
Inline callers:
  - kernel/irq/proc.c:init_irq_proc
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff810edf30-ffffffff810ee072: register_irq_proc.part.6 (STB_LOCAL)
ffffffff810ee560-ffffffff810ee585: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff810edea0)
Location: kernel/irq/proc.c:392
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff810edea0-ffffffff810ee03a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff810f68e0)
Location: kernel/irq/proc.c:394
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff810f68e0-ffffffff810f6a7a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff810fec00)
Location: kernel/irq/proc.c:330
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff810fec00-ffffffff810fed9a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff8110a3d0)
Location: kernel/irq/proc.c:330
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff8110a3d0-ffffffff8110a56a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff81113ab0)
Location: kernel/irq/proc.c:330
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff81113ab0-ffffffff81113c4a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff8111fc20)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff8111fc20-ffffffff8111fdba: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff8112c160)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff8112c160-ffffffff8112c2fa: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff81127b80)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff81127b80-ffffffff81127d1a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff81127e40)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff81127e40-ffffffff81127fda: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff811483b0)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff811483b0-ffffffff8114854a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff8116ce70)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff8116ce70-ffffffff8116d029: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff811a1f90)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff811a1f90-ffffffff811a2149: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff811b3e90)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff811b3e90-ffffffff811b4049: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff811c3d10)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff811c3d10-ffffffff811c3ec9: register_irq_proc (STB_GLOBAL)
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
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffff8000101859e0)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffff8000101859e0-ffff800010185b94: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (c03d48cc)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
c03d48cc-c03d4a80: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (c0000000001e0030)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
c0000000001e0030-c0000000001e0218: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffe00011c490)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffe00011c490-ffffffe00011c5cc: register_irq_proc (STB_GLOBAL)
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
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff81118200)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff81118200-ffffffff8111839a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff81109270)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff81109270-ffffffff8110940a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff811160f0)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff811160f0-ffffffff8111628a: register_irq_proc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void register_irq_proc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/proc.c (ffffffff81121720)
Location: kernel/irq/proc.c:338
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/proc.c:init_irq_proc
```
**Symbols:**

```
ffffffff81121720-ffffffff811218ba: register_irq_proc (STB_GLOBAL)
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
