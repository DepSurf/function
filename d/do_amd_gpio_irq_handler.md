# Function: <code>do_amd_gpio_irq_handler</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool do_amd_gpio_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff8167d390)
Location: drivers/pinctrl/pinctrl-amd.c:601
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_check_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff8167d390-ffffffff8167d593: do_amd_gpio_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool do_amd_gpio_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81798e70)
Location: drivers/pinctrl/pinctrl-amd.c:606
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_check_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff81798e70-ffffffff8179906e: do_amd_gpio_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool do_amd_gpio_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818aee70)
Location: drivers/pinctrl/pinctrl-amd.c:603
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_check_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff818aee70-ffffffff818af0bb: do_amd_gpio_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool do_amd_gpio_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f1dc0)
Location: drivers/pinctrl/pinctrl-amd.c:595
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_check_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff818f1dc0-ffffffff818f2009: do_amd_gpio_irq_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool do_amd_gpio_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff819395f0)
Location: drivers/pinctrl/pinctrl-amd.c:595
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_check_wake
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff819395f0-ffffffff81939839: do_amd_gpio_irq_handler (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
