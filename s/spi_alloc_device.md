# Function: <code>spi_alloc_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct spi_device *spi_alloc_device(struct spi_master *master);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e8be0)
Location: drivers/spi/spi.c:438
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_new_device
  - drivers/spi/spi.c:acpi_spi_add_device
```
**Symbols:**

```
ffffffff815e8be0-ffffffff815e8c79: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct spi_device *spi_alloc_device(struct spi_master *master);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81647150)
Location: drivers/spi/spi.c:441
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81647150-ffffffff816471e6: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct spi_device *spi_alloc_device(struct spi_master *master);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81678240)
Location: drivers/spi/spi.c:442
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81678240-ffffffff816782d6: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168c940)
Location: drivers/spi/spi.c:444
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8168c940-ffffffff8168c9db: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f62f0)
Location: drivers/spi/spi.c:448
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff816f62f0-ffffffff816f638b: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817316f0)
Location: drivers/spi/spi.c:452
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817316f0-ffffffff8173178b: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817540e0)
Location: drivers/spi/spi.c:492
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817540e0-ffffffff8175417c: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8178f890)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8178f890-ffffffff8178f92d: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b3450)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817b3450-ffffffff817b3502: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187a430)
Location: drivers/spi/spi.c:501
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8187a430-ffffffff8187a4e2: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81888e90)
Location: drivers/spi/spi.c:510
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81888e90-ffffffff81888f42: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186a860)
Location: drivers/spi/spi.c:506
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff8186a860-ffffffff8186a912: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fac00)
Location: drivers/spi/spi.c:539
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff818fac00-ffffffff818facb2: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4c350)
Location: drivers/spi/spi.c:509
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81a4c350-ffffffff81a4c3f3: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd5250)
Location: drivers/spi/spi.c:566
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81bd5250-ffffffff81bd539c: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2b520)
Location: drivers/spi/spi.c:567
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81c2b520-ffffffff81c2b60c: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cde020)
Location: drivers/spi/spi.c:567
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:spi_new_ancillary_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81cde020-ffffffff81cde13b: spi_alloc_device (STB_GLOBAL)
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
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c2450)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffff8000109c2450-ffff8000109c2500: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aaf258)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
c0aaf258-c0aaf300: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a87730)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
c000000000a87730-c000000000a87828: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000617856)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:of_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffe000617856-ffffffe000617902: spi_alloc_device (STB_GLOBAL)
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
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81777f30)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81777f30-ffffffff81777fe2: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81757ce0)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff81757ce0-ffffffff81757d92: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817a82d0)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817a82d0-ffffffff817a8382: spi_alloc_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct spi_device *spi_alloc_device(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c2160)
Location: drivers/spi/spi.c:495
Inline: False
Direct callers:
  - drivers/spi/spi.c:slave_store
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/spi/spi.c:spi_new_device
```
**Symbols:**

```
ffffffff817c2160-ffffffff817c2212: spi_alloc_device (STB_GLOBAL)
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
<code>struct spi_controller *ctlr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct spi_master *master</code>
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
