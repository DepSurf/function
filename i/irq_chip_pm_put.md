# Function: <code>irq_chip_pm_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e44d0)
Location: kernel/irq/chip.c:1185
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810e44d0-ffffffff810e44fc: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ead70)
Location: kernel/irq/chip.c:1194
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810ead70-ffffffff810ead9c: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea430)
Location: kernel/irq/chip.c:1312
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810ea430-ffffffff810ea45c: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f2940)
Location: kernel/irq/chip.c:1444
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810f2940-ffffffff810f296c: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810fad40)
Location: kernel/irq/chip.c:1442
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810fad40-ffffffff810fad6c: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81106500)
Location: kernel/irq/chip.c:1442
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81106500-ffffffff8110652c: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110fa80)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8110fa80-ffffffff8110fab1: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111bd40)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8111bd40-ffffffff8111bd71: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81128070)
Location: kernel/irq/chip.c:1601
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff81128070-ffffffff811280a3: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123b80)
Location: kernel/irq/chip.c:1588
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff81123b80-ffffffff81123bb3: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123ee0)
Location: kernel/irq/chip.c:1591
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff81123ee0-ffffffff81123f0b: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811444c0)
Location: kernel/irq/chip.c:1591
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff811444c0-ffffffff811444eb: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811680ab)
Location: kernel/irq/chip.c:1596
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff81168360-ffffffff811683a5: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c56b)
Location: kernel/irq/chip.c:1598
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff8119c860-ffffffff8119c8a5: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae3df)
Location: kernel/irq/chip.c:1613
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff811ae6e0-ffffffff811ae725: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bdfdf)
Location: kernel/irq/chip.c:1610
Inline: True
Inline callers:
  - kernel/irq/chip.c:__irq_do_set_handler
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
```
**Symbols:**

```
ffffffff811be2e0-ffffffff811be325: irq_chip_pm_put (STB_GLOBAL)
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
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff800010180168)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffff800010180168-ffff8000101801b8: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03d01b8)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
c03d01b8-c03d01ec: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001dad20)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
c0000000001dad20-c0000000001dad88: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000118388)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffe000118388-ffffffe0001183d0: irq_chip_pm_put (STB_GLOBAL)
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
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81114320)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81114320-ffffffff81114351: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105030)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81105030-ffffffff81105061: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112210)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81112210-ffffffff81112241: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_chip_pm_put(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111d830)
Location: kernel/irq/chip.c:1557
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:__free_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__cleanup_nmi
  - kernel/irq/manage.c:__free_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8111d830-ffffffff8111d861: irq_chip_pm_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
