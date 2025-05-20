# Function: <code>amba_aphb_device_add</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct amba_device *amba_aphb_device_add(struct device *parent, const char *name, resource_size_t base, size_t size, int irq1, int irq2, void *pdata, unsigned int periphid, u64 dma_mask, struct resource *resbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (ffff8000107b9b10)
Location: drivers/amba/bus.c:569
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_ahb_device_add_res
  - drivers/amba/bus.c:amba_apb_device_add_res
  - drivers/amba/bus.c:amba_ahb_device_add
  - drivers/amba/bus.c:amba_apb_device_add
```
**Symbols:**

```
ffff8000107b9b10-ffff8000107b9bf4: amba_aphb_device_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct amba_device *amba_aphb_device_add(struct device *parent, const char *name, resource_size_t base, size_t size, int irq1, int irq2, void *pdata, unsigned int periphid, u64 dma_mask, struct resource *resbase);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (c08e5bc4)
Location: drivers/amba/bus.c:569
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_ahb_device_add_res
  - drivers/amba/bus.c:amba_apb_device_add_res
  - drivers/amba/bus.c:amba_ahb_device_add
  - drivers/amba/bus.c:amba_apb_device_add
```
**Symbols:**

```
c08e5bc4-c08e5c58: amba_aphb_device_add (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
