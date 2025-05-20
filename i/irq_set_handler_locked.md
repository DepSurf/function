# Function: <code>irq_set_handler_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81421eb5)
Location: include/linux/irqdesc.h:183
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81423047)
Location: include/linux/irqdesc.h:183
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8146a1b6)
Location: include/linux/irqdesc.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8146bdcb)
Location: include/linux/irqdesc.h:190
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81489afd)
Location: include/linux/irqdesc.h:193
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8148c19b)
Location: include/linux/irqdesc.h:193
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148e2f9)
Location: include/linux/irqdesc.h:193
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8149330b)
Location: include/linux/irqdesc.h:200
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81495d96)
Location: include/linux/irqdesc.h:200
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81498077)
Location: include/linux/irqdesc.h:200
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff814cf591)
Location: include/linux/irqdesc.h:202
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff814d209d)
Location: include/linux/irqdesc.h:202
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d42e7)
Location: include/linux/irqdesc.h:202
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff814d5ea1)
Location: include/linux/irqdesc.h:202
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815007b8)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8150309d)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81505303)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815151ed)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8151799d)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81519bf3)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815433a7)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81545b9d)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81547d41)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815642b7)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81566abb)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81568c61)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81574458)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff816067e5)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81608ed6)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160c1a1)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8162aad2)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8162d5e6)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816309e8)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81632012)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8160e7b2)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81611256)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81614688)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81615c22)
Location: include/linux/irqdesc.h:201
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167d652)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81680506)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81683878)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81684ff7)
Location: include/linux/irqdesc.h:197
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81799126)
Location: include/linux/irqdesc.h:191
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8179c48e)
Location: include/linux/irqdesc.h:191
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179fe3b)
Location: include/linux/irqdesc.h:191
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff817a17d7)
Location: include/linux/irqdesc.h:191
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818af1a6)
Location: include/linux/irqdesc.h:192
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818b2eae)
Location: include/linux/irqdesc.h:192
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b6c5a)
Location: include/linux/irqdesc.h:192
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818b8927)
Location: include/linux/irqdesc.h:192
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f2167)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff818f5efe)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f9cce)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff818fb9c3)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81939997)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8193e48a)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff819410f0)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-intel.c (ffffffff81942ff3)
Location: include/linux/irqdesc.h:195
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_type
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-ti-sci-inta.c (ffff80001067e2d0)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/irqchip/irq-ti-sci-inta.c:ti_sci_inta_set_type
```
```
In drivers/pinctrl/pinctrl-amd.c (ffff800010694134)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/pinctrl-rockchip.c (ffff80001069b29c)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (ffff8000106a12b8)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (ffff8000106a3f4c)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
  - drivers/pinctrl/bcm/pinctrl-bcm2835.c:bcm2835_gpio_irq_set_type
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106af1c0)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
```
```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106cec68)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
```
In drivers/gpio/gpio-pl061.c (ffff8000106d3c40)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c0834c0c)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/pinctrl-rockchip.c (c0838e24)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
  - drivers/pinctrl/pinctrl-rockchip.c:rockchip_irq_set_type
```
```
In drivers/pinctrl/actions/pinctrl-owl.c (c084556c)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
  - drivers/pinctrl/actions/pinctrl-owl.c:owl_gpio_irq_set_type
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084d7d4)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_set_irq_type
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_set_irq_type
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (c084fa04)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_set_type
```
```
In drivers/pinctrl/samsung/pinctrl-exynos.c (c0851fcc)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_set_type
```
```
In drivers/gpio/gpio-ftgpio010.c (c0868548)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
```
In drivers/gpio/gpio-omap.c (c086cc14)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
  - drivers/gpio/gpio-omap.c:omap_gpio_irq_type
```
```
In drivers/gpio/gpio-pl061.c (c086effc)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
  - drivers/gpio/gpio-pl061.c:pl061_irq_type
```
```
In drivers/gpio/gpio-tegra.c (c0871454)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
```
```
In drivers/gpio/gpio-vf610.c (c08733ac)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_type
  - drivers/gpio/gpio-vf610.c:vf610_gpio_irq_set_type
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (c000000000830fec)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpio-ftgpio010.c (c00000000084a1a0)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffe00049e72c)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae580)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8155c8a7)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155df8b)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8154d0cb)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154f271)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155aa68)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff815585e7)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff8155adeb)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155cf91)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568788)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81572477)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_set_type
```
```
In drivers/pinctrl/intel/pinctrl-baytrail.c (ffffffff81574c7b)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_type
```
```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81576e21)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_type
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
```
```
In drivers/gpio/gpio-lynxpoint.c (ffffffff815826a8)
Location: include/linux/irqdesc.h:204
Inline: True
Inline callers:
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
  - drivers/gpio/gpio-lynxpoint.c:lp_irq_type
```
</details>
</li>
</ul>

## Differences
