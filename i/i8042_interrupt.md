# Function: <code>i8042_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81664c20)
Location: drivers/input/serio/i8042.c:464
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81664c20-ffffffff81664fd9: i8042_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816c4e50)
Location: drivers/input/serio/i8042.c:464
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff816c4e50-ffffffff816c521b: i8042_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff816f2e70)
Location: drivers/input/serio/i8042.c:494
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff816f2e70-ffffffff816f323b: i8042_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff817087a0)
Location: drivers/input/serio/i8042.c:502
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff817087a0-ffffffff81708b46: i8042_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (ffffffff81779990)
Location: drivers/input/serio/i8042.c:502
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81779990-ffffffff81779d39: i8042_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:502
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff817ba620-ffffffff817ba86d: i8042_interrupt (STB_LOCAL)
ffffffff817bb67c-ffffffff817bb7f9: i8042_interrupt.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:502
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff817e1a40-ffffffff817e1cda: i8042_interrupt (STB_LOCAL)
ffffffff817e2aec-ffffffff817e2c54: i8042_interrupt.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:498
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81822340-ffffffff8182258f: i8042_interrupt (STB_LOCAL)
ffffffff8182346f-ffffffff818235da: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff818537b0-ffffffff818539ff: i8042_interrupt (STB_LOCAL)
ffffffff8185492f-ffffffff81854a9a: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:514
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff819259b0-ffffffff81925c05: i8042_interrupt (STB_LOCAL)
ffffffff81926c78-ffffffff81926de4: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:537
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff8192d510-ffffffff8192d765: i8042_interrupt (STB_LOCAL)
ffffffff81c22b42-ffffffff81c22cae: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:537
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81910960-ffffffff81910bb5: i8042_interrupt (STB_LOCAL)
ffffffff81c14dc4-ffffffff81c14f30: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:541
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff819b18b0-ffffffff819b1c0a: i8042_interrupt (STB_LOCAL)
ffffffff81d2248a-ffffffff81d227e0: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:541
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81b104e0-ffffffff81b1088f: i8042_interrupt (STB_LOCAL)
ffffffff81eee05e-ffffffff81eee3d5: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:541
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81ca0c20-ffffffff81ca10da: i8042_interrupt (STB_LOCAL)
ffffffff820a5f9b-ffffffff820a61a0: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:541
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81d07f70-ffffffff81d08424: i8042_interrupt (STB_LOCAL)
ffffffff821273a4-ffffffff821275a7: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:541
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81dbdba0-ffffffff81dbe054: i8042_interrupt (STB_LOCAL)
ffffffff82208d25-ffffffff82208f28: i8042_interrupt.cold (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/i8042.c (c000000000b71910)
Location: drivers/input/serio/i8042.c:512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
c000000000b71910-c000000000b71ee0: i8042_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_restore
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_pm_resume_noirq
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81808890-ffffffff81808adf: i8042_interrupt (STB_LOCAL)
ffffffff8180993f-ffffffff81809aaa: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff817cff70-ffffffff817d01bf: i8042_interrupt (STB_LOCAL)
ffffffff817d10df-ffffffff817d124a: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81847940-ffffffff81847b8f: i8042_interrupt (STB_LOCAL)
ffffffff81848abf-ffffffff81848c2a: i8042_interrupt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t i8042_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/i8042.c (0)
Location: drivers/input/serio/i8042.c:512
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_pm_thaw
  - drivers/input/serio/i8042.c:i8042_controller_resume
  - drivers/input/serio/i8042.c:i8042_port_close
```
**Symbols:**

```
ffffffff81862b80-ffffffff81862dcf: i8042_interrupt (STB_LOCAL)
ffffffff81863cdf-ffffffff81863e4a: i8042_interrupt.cold (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
