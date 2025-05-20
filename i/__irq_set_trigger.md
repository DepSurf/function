# Function: <code>__irq_set_trigger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810dc4d0)
Location: kernel/irq/manage.c:648
Inline: False
Direct callers:
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff810dc4d0-ffffffff810dc65f: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e1be0)
Location: kernel/irq/manage.c:662
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff810e1be0-ffffffff810e1d61: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e8510)
Location: kernel/irq/manage.c:662
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff810e8510-ffffffff810e8677: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7a30)
Location: kernel/irq/manage.c:639
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff810e7a30-ffffffff810e7b98: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810efdb0)
Location: kernel/irq/manage.c:667
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff810efdb0-ffffffff810eff1b: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f81f0)
Location: kernel/irq/manage.c:700
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff810f81f0-ffffffff810f835c: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81103990)
Location: kernel/irq/manage.c:703
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81103990-ffffffff81103afc: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:769
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff8110d77d-ffffffff8110d79a: __irq_set_trigger.cold (STB_LOCAL)
ffffffff8110c3e0-ffffffff8110c54e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81119aff-ffffffff81119b1c: __irq_set_trigger.cold (STB_LOCAL)
ffffffff811187c0-ffffffff8111892e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:845
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81125a29-ffffffff81125a46: __irq_set_trigger.cold (STB_LOCAL)
ffffffff811240b0-ffffffff8112421e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:915
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81be1761-ffffffff81be177e: __irq_set_trigger.cold (STB_LOCAL)
ffffffff8111ff10-ffffffff8112007e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:915
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81bd381c-ffffffff81bd3839: __irq_set_trigger.cold (STB_LOCAL)
ffffffff811201d0-ffffffff8112033e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:939
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81cad6ba-ffffffff81cad6d7: __irq_set_trigger.cold (STB_LOCAL)
ffffffff81140700-ffffffff8114086b: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:954
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81e5dbda-ffffffff81e5dbf5: __irq_set_trigger.cold (STB_LOCAL)
ffffffff811640f0-ffffffff81164251: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81197e90)
Location: kernel/irq/manage.c:946
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81197e90-ffffffff8119800b: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a9b50)
Location: kernel/irq/manage.c:952
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff811a9b50-ffffffff811a9ce3: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b96b0)
Location: kernel/irq/manage.c:954
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff811b96b0-ffffffff811b9843: __irq_set_trigger (STB_GLOBAL)
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
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017b110)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffff80001017b110-ffff80001017b2cc: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cc240)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
c03cc240-c03cc3f4: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d5730)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
c0000000001d5730-c0000000001d5970: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000114cf6)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffe000114cf6-ffffffe000114e6c: __irq_set_trigger (STB_GLOBAL)
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
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff811120df-ffffffff811120fc: __irq_set_trigger.cold (STB_LOCAL)
ffffffff81110da0-ffffffff81110f0e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff81102e0f-ffffffff81102e2c: __irq_set_trigger.cold (STB_LOCAL)
ffffffff81101ad0-ffffffff81101c3e: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff8110ffcf-ffffffff8110ffec: __irq_set_trigger.cold (STB_LOCAL)
ffffffff8110ec90-ffffffff8110edfe: __irq_set_trigger (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __irq_set_trigger(struct irq_desc *desc, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:762
Inline: False
Direct callers:
  - kernel/irq/manage.c:enable_percpu_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/chip.c:__irq_do_set_handler
  - kernel/irq/chip.c:irq_set_irq_type
```
**Symbols:**

```
ffffffff8111b53f-ffffffff8111b55c: __irq_set_trigger.cold (STB_LOCAL)
ffffffff8111a1c0-ffffffff8111a32e: __irq_set_trigger (STB_GLOBAL)
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
