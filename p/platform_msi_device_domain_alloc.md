# Function: <code>platform_msi_device_domain_alloc</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int platform_msi_device_domain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff819b4610)
Location: drivers/base/platform-msi.c:343
Inline: False
```
**Symbols:**

```
ffffffff819b4610-ffffffff819b4648: platform_msi_device_domain_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int platform_msi_device_domain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81b29590)
Location: drivers/base/platform-msi.c:345
Inline: False
```
**Symbols:**

```
ffffffff81b29590-ffffffff81b295c8: platform_msi_device_domain_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int platform_msi_device_domain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81b79740)
Location: drivers/base/platform-msi.c:345
Inline: False
```
**Symbols:**

```
ffffffff81b79740-ffffffff81b7977b: platform_msi_device_domain_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int platform_msi_device_domain_alloc(struct irq_domain *domain, unsigned int virq, unsigned int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff81bcd670)
Location: drivers/base/platform-msi.c:345
Inline: False
```
**Symbols:**

```
ffffffff81bcd670-ffffffff81bcd6ab: platform_msi_device_domain_alloc (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
