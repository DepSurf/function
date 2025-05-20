# Function: <code>irq_activate</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f201c)
Location: kernel/irq/chip.c:288
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff810f1da0-ffffffff810f1dc7: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa465)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff810fa1e0-ffffffff810fa207: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105c25)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff811059a0-ffffffff811059c7: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110f0e5)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff8110ee90-ffffffff8110eeb7: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b3a5)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff8111b150-ffffffff8111b177: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127545)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81127250-ffffffff81127277: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123145)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81122e50-ffffffff81122e77: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811234a5)
Location: kernel/irq/chip.c:289
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81123150-ffffffff81123177: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143a75)
Location: kernel/irq/chip.c:289
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81143720-ffffffff81143747: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167865)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff811674b0-ffffffff811674eb: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119bc45)
Location: kernel/irq/chip.c:288
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff8119b830-ffffffff8119b86b: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae30e)
Location: kernel/irq/chip.c:288
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff811ad670-ffffffff811ad6ab: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bdf0e)
Location: kernel/irq/chip.c:288
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff811bd270-ffffffff811bd2ab: irq_activate (STB_GLOBAL)
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
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f394)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffff80001017f058-ffff80001017f0a4: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf5b0)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
c03cf274-c03cf2ac: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9d50)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
c0000000001d9950-c0000000001d9978: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001178e8)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffe00011763c-ffffffe000117682: irq_activate (STB_GLOBAL)
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
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113985)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81113730-ffffffff81113757: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104695)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81104440-ffffffff81104467: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111875)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff81111620-ffffffff81111647: irq_activate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int irq_activate(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111ce35)
Location: kernel/irq/chip.c:286
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_activate_and_startup
Direct callers:
  - kernel/irq/manage.c:__setup_irq
```
**Symbols:**

```
ffffffff8111cbe0-ffffffff8111cc07: irq_activate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
