# Function: <code>amba_put_disable_pclk</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/amba/bus.c (ffff8000107b92d8)
Location: drivers/amba/bus.c:247
Inline: True
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
**Symbols:**

```
ffff8000107b92d8-ffff8000107b9318: amba_put_disable_pclk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void amba_put_disable_pclk(struct amba_device *pcdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (c08e5170)
Location: drivers/amba/bus.c:247
Inline: False
Direct callers:
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_device_try_add
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
**Symbols:**

```
c08e5170-c08e51a8: amba_put_disable_pclk (STB_LOCAL)
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
