# Function: <code>i2c_dev_irq_from_resources</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81720c93)
Location: drivers/i2c/i2c-core-base.c:682
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/i2c/i2c-core-base.c (ffffffff81792006)
Location: drivers/i2c/i2c-core-base.c:693
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/i2c/i2c-core-base.c (ffffffff817d49c1)
Location: drivers/i2c/i2c-core-base.c:674
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
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
In drivers/i2c/i2c-core-base.c (ffffffff817fbada)
Location: drivers/i2c/i2c-core-base.c:686
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183c920)
Location: drivers/i2c/i2c-core-base.c:684
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8183c920-ffffffff8183c999: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186e320)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8186e320-ffffffff8186e399: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81942100)
Location: drivers/i2c/i2c-core-base.c:699
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81942100-ffffffff81942182: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81948450)
Location: drivers/i2c/i2c-core-base.c:827
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff81948450-ffffffff819484ca: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192bdb0)
Location: drivers/i2c/i2c-core-base.c:871
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8192bdb0-ffffffff8192be32: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cef70)
Location: drivers/i2c/i2c-core-base.c:872
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff819cef70-ffffffff819ceff2: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b30cf0)
Location: drivers/i2c/i2c-core-base.c:873
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_resource
```
**Symbols:**

```
ffffffff81b30cf0-ffffffff81b30da6: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc5660)
Location: drivers/i2c/i2c-core-base.c:874
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource
```
**Symbols:**

```
ffffffff81cc5660-ffffffff81cc5716: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2d2f0)
Location: drivers/i2c/i2c-core-base.c:889
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource
```
**Symbols:**

```
ffffffff81d2d2f0-ffffffff81d2d3a6: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de31e0)
Location: drivers/i2c/i2c-core-base.c:892
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource
```
**Symbols:**

```
ffffffff81de31e0-ffffffff81de3296: i2c_dev_irq_from_resources (STB_GLOBAL)
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
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab19a8)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffff800010ab19a8-ffff800010ab1a78: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b930e4)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
c0b930e4-c0b93188: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b94e50)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
c000000000b94e50-c000000000b94f68: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b97d0)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffe0006b97d0-ffffffe0006b9866: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff818624b0)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff818624b0-ffffffff81862529: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int i2c_dev_irq_from_resources(const struct resource *resources, unsigned int num_resources);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187d710)
Location: drivers/i2c/i2c-core-base.c:689
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
**Symbols:**

```
ffffffff8187d710-ffffffff8187d789: i2c_dev_irq_from_resources (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
