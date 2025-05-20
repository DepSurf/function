# Function: <code>irq_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810de1f0)
Location: kernel/irq/chip.c:189
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810de1f0-ffffffff810de26e: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e3b40)
Location: kernel/irq/chip.c:189
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810e3b40-ffffffff810e3bbe: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea390)
Location: kernel/irq/chip.c:188
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
```
**Symbols:**

```
ffffffff810ea390-ffffffff810ea40b: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9a40)
Location: kernel/irq/chip.c:251
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/autoprobe.c:probe_irq_on
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810e9a40-ffffffff810e9b0d: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1f20)
Location: kernel/irq/chip.c:257
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810f1f20-ffffffff810f2009: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fa360)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff810fa360-ffffffff810fa458: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105b20)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81105b20-ffffffff81105c18: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (0)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8110fab1-ffffffff8110fac4: irq_startup.cold (STB_LOCAL)
ffffffff8110efe0-ffffffff8110f0d7: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111b2a0)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111b2a0-ffffffff8111b397: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81127470)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81127470-ffffffff81127532: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123070)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81123070-ffffffff81123132: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123370)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81123370-ffffffff8112349a: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81143940)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81143940-ffffffff81143a6a: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167710)
Location: kernel/irq/chip.c:252
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81167710-ffffffff8116785f: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119bae0)
Location: kernel/irq/chip.c:254
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8119bae0-ffffffff8119bc2f: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ad930)
Location: kernel/irq/chip.c:254
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811ad930-ffffffff811ada85: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bd530)
Location: kernel/irq/chip.c:254
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff811bd530-ffffffff811bd685: irq_startup (STB_GLOBAL)
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
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017f248)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffff80001017f248-ffff80001017f378: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03cf444)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c03cf444-c03cf59c: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d9bb0)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
c0000000001d9bb0-c0000000001d9d38: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001177d4)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
```
**Symbols:**

```
ffffffe0001177d4-ffffffe0001178ce: irq_startup (STB_GLOBAL)
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
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81113880)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81113880-ffffffff81113977: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104590)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81104590-ffffffff81104687: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81111770)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff81111770-ffffffff81111867: irq_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_startup(struct irq_desc *desc, bool resend, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111cd30)
Location: kernel/irq/chip.c:255
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:irq_activate_and_startup
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
```
**Symbols:**

```
ffffffff8111cd30-ffffffff8111ce27: irq_startup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force</code>
</li>
</ul>
</details>
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
