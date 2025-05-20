# Function: <code>platform_msi_create_device_domain</code>

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
struct irq_domain *platform_msi_create_device_domain(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815c2400)
Location: drivers/base/platform-msi.c:333
Inline: False
```
**Symbols:**

```
ffffffff815c2400-ffffffff815c24c4: platform_msi_create_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *platform_msi_create_device_domain(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff815f1850)
Location: drivers/base/platform-msi.c:332
Inline: False
```
**Symbols:**

```
ffffffff815f1850-ffffffff815f1904: platform_msi_create_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *platform_msi_create_device_domain(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816059a0)
Location: drivers/base/platform-msi.c:332
Inline: False
```
**Symbols:**

```
ffffffff816059a0-ffffffff81605a54: platform_msi_create_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *platform_msi_create_device_domain(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff8166dda0)
Location: drivers/base/platform-msi.c:332
Inline: False
```
**Symbols:**

```
ffffffff8166dda0-ffffffff8166de54: platform_msi_create_device_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *platform_msi_create_device_domain(struct device *dev, unsigned int nvec, irq_write_msi_msg_t write_msi_msg, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/platform-msi.c (ffffffff816a9810)
Location: drivers/base/platform-msi.c:324
Inline: False
```
**Symbols:**

```
ffffffff816a9810-ffffffff816a98c1: platform_msi_create_device_domain (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
