# Function: <code>irq_activate_and_startup</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f2010)
Location: kernel/irq/chip.c:297
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810f2010-ffffffff810f205b: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa460)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810fa460-ffffffff810fa4a8: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105c20)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81105c20-ffffffff81105c68: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (0)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff8110fac4-ffffffff8110fad9: irq_activate_and_startup.cold (STB_LOCAL)
ffffffff8110f0e0-ffffffff8110f128: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b3a0)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff8111b3a0-ffffffff8111b3eb: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127540)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81127540-ffffffff8112758b: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123140)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81123140-ffffffff8112318b: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811234a0)
Location: kernel/irq/chip.c:298
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff811234a0-ffffffff811234eb: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143a70)
Location: kernel/irq/chip.c:298
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81143a70-ffffffff81143abb: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167860)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81167860-ffffffff811678bf: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119bc40)
Location: kernel/irq/chip.c:297
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff8119bc40-ffffffff8119bc9f: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae30e)
Location: kernel/irq/chip.c:297
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff811adaa0-ffffffff811adaff: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bdf0e)
Location: kernel/irq/chip.c:297
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff811bd6a0-ffffffff811bd6ff: irq_activate_and_startup (STB_GLOBAL)
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
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f378)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffff80001017f378-ffff80001017f3e0: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf59c)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
c03cf59c-c03cf610: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9d40)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:__irq_do_set_handler
```
**Symbols:**

```
c0000000001d9d40-c0000000001d9d70: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001178ce)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
```
**Symbols:**

```
ffffffe0001178ce-ffffffe00011792e: irq_activate_and_startup (STB_GLOBAL)
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
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113980)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81113980-ffffffff811139cb: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104690)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81104690-ffffffff811046db: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111870)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff81111870-ffffffff811118bb: irq_activate_and_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_activate_and_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111ce30)
Location: kernel/irq/chip.c:295
Inline: False
Direct callers:
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff8111ce30-ffffffff8111ce7b: irq_activate_and_startup (STB_GLOBAL)
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
