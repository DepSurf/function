# Function: <code>irq_chip_pm_get</code>

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
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e4450)
Location: kernel/irq/chip.c:1162
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810e4450-ffffffff810e44c5: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810eacf0)
Location: kernel/irq/chip.c:1171
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810eacf0-ffffffff810ead65: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea3c0)
Location: kernel/irq/chip.c:1289
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810ea3c0-ffffffff810ea42c: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f28d0)
Location: kernel/irq/chip.c:1421
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810f28d0-ffffffff810f293c: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810facd0)
Location: kernel/irq/chip.c:1419
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff810facd0-ffffffff810fad3f: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81106490)
Location: kernel/irq/chip.c:1419
Inline: False
Direct callers:
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81106490-ffffffff811064ff: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110fa20)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8110fa20-ffffffff8110fa73: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111bce0)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8111bce0-ffffffff8111bd33: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81128010)
Location: kernel/irq/chip.c:1578
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81128010-ffffffff81128066: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123b20)
Location: kernel/irq/chip.c:1565
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81123b20-ffffffff81123b76: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81123e80)
Location: kernel/irq/chip.c:1568
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81123e80-ffffffff81123ed6: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81144460)
Location: kernel/irq/chip.c:1568
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
```
**Symbols:**

```
ffffffff81144460-ffffffff811444b6: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167eb0)
Location: kernel/irq/chip.c:1577
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/chip.c:__irq_do_set_handler
```
**Symbols:**

```
ffffffff81167eb0-ffffffff81167f1d: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119c360)
Location: kernel/irq/chip.c:1579
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/chip.c:__irq_do_set_handler
```
**Symbols:**

```
ffffffff8119c360-ffffffff8119c3cd: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ae1b0)
Location: kernel/irq/chip.c:1594
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/chip.c:__irq_do_set_handler
```
**Symbols:**

```
ffffffff811ae1b0-ffffffff811ae21d: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bddb0)
Location: kernel/irq/chip.c:1591
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/chip.c:__irq_do_set_handler
```
**Symbols:**

```
ffffffff811bddb0-ffffffff811bde1d: irq_chip_pm_get (STB_GLOBAL)
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
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff8000101800d0)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffff8000101800d0-ffff800010180168: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03d0130)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
c03d0130-c03d01b8: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001dac70)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
c0000000001dac70-c0000000001dad1c: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe000118326)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffe000118326-ffffffe000118388: irq_chip_pm_get (STB_GLOBAL)
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
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811142c0)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff811142c0-ffffffff81114313: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81104fd0)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff81104fd0-ffffffff81105023: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811121b0)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff811121b0-ffffffff81112203: irq_chip_pm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int irq_chip_pm_get(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111d7d0)
Location: kernel/irq/chip.c:1534
Inline: False
Direct callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:setup_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:setup_irq
```
**Symbols:**

```
ffffffff8111d7d0-ffffffff8111d823: irq_chip_pm_get (STB_GLOBAL)
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
