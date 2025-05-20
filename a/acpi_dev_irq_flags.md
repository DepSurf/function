# Function: <code>acpi_dev_irq_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8148188a)
Location: drivers/acpi/resource.c:321
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff8148188a-ffffffff814818bf: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814d0342)
Location: drivers/acpi/resource.c:334
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff814d0342-ffffffff814d0377: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814f22ac)
Location: drivers/acpi/resource.c:347
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
```
**Symbols:**

```
ffffffff814f22ac-ffffffff814f22e1: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814ffbc0)
Location: drivers/acpi/resource.c:347
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff814ffbc0-ffffffff814ffbf8: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81541d70)
Location: drivers/acpi/resource.c:347
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81541d70-ffffffff81541da8: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81577cc0)
Location: drivers/acpi/resource.c:347
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81577cc0-ffffffff81577cf8: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8158f900)
Location: drivers/acpi/resource.c:347
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8158f900-ffffffff8158f938: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c0750)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815c0750-ffffffff815c0788: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e1a10)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815e1a10-ffffffff815e1a48: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168c820)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8168c820-ffffffff8168c858: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aa520)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff816aa520-ffffffff816aa558: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168cda0)
Location: drivers/acpi/resource.c:340
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8168cda0-ffffffff8168cdd8: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff817025d0)
Location: drivers/acpi/resource.c:340
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff817025d0-ffffffff81702608: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81830700)
Location: drivers/acpi/resource.c:340
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81830370-ffffffff818303b4: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable, u8 wake_capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8196434e)
Location: drivers/acpi/resource.c:341
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81963730-ffffffff81963782: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable, u8 wake_capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aa7de)
Location: drivers/acpi/resource.c:341
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff819a9be0-ffffffff819a9c32: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable, u8 wake_capable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f4a6c)
Location: drivers/acpi/resource.c:341
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_get_irqresource
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff819f3e70-ffffffff819f3ec2: acpi_dev_irq_flags (STB_GLOBAL)
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
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076e150)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffff80001076e150-ffff80001076e1d0: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d3cd0)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815d3cd0-ffffffff815d3d08: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815bd890)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815bd890-ffffffff815bd8c8: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d5cf0)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815d5cf0-ffffffff815d5d28: acpi_dev_irq_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int acpi_dev_irq_flags(u8 triggering, u8 polarity, u8 shareable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815efbb0)
Location: drivers/acpi/resource.c:339
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_option_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815efbb0-ffffffff815efbe8: acpi_dev_irq_flags (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 wake_capable</code>
</li>
</ul>
</details>
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
