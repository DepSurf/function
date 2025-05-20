# Function: <code>irq_settings_get_trigger_mask</code>

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
In kernel/irq/manage.c (ffffffff810dcafc)
Location: kernel/irq/settings.h:68
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/chip.c (0)
Location: kernel/irq/settings.h:68
Inline: True
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
In kernel/irq/manage.c (ffffffff810e2206)
Location: kernel/irq/settings.h:68
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/chip.c (ffffffff810e3251)
Location: kernel/irq/settings.h:68
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9b1b)
Location: kernel/irq/settings.h:68
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (0)
Location: kernel/irq/settings.h:68
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (0)
Location: kernel/irq/settings.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f98ce)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110507e)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110e365)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111a625)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811266a5)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811222d9)
Location: kernel/irq/settings.h:71
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122659)
Location: kernel/irq/settings.h:71
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81142c09)
Location: kernel/irq/settings.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811668b1)
Location: kernel/irq/settings.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119ab61)
Location: kernel/irq/settings.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ac8c1)
Location: kernel/irq/settings.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bc4c1)
Location: kernel/irq/settings.h:73
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffff80001017dcb0)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c03ce488)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (c0000000001d85d0)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffe0001168ac)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81112c05)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81103925)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81110af5)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111c075)
Location: kernel/irq/settings.h:69
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_modify_status
```
</details>
</li>
</ul>

## Differences
