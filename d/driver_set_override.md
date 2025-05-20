# Function: <code>driver_set_override</code>

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
int driver_set_override(struct device *dev, const char **override, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff8197ec20)
Location: drivers/base/driver.c:48
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/spi/spi.c:driver_override_store
```
**Symbols:**

```
ffffffff8197ec20-ffffffff8197ed75: driver_set_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int driver_set_override(struct device *dev, const char **override, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81aec2f0)
Location: drivers/base/driver.c:48
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/spi/spi.c:driver_override_store
```
**Symbols:**

```
ffffffff81aec2f0-ffffffff81aec44d: driver_set_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int driver_set_override(struct device *dev, const char **override, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b3a4e0)
Location: drivers/base/driver.c:48
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/spi/spi.c:driver_override_store
```
**Symbols:**

```
ffffffff81b3a4e0-ffffffff81b3a63d: driver_set_override (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int driver_set_override(struct device *dev, const char **override, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/driver.c (ffffffff81b91fa0)
Location: drivers/base/driver.c:48
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:driver_override_store
  - drivers/base/platform.c:driver_override_store
  - drivers/spi/spi.c:driver_override_store
```
**Symbols:**

```
ffffffff81b91fa0-ffffffff81b920fd: driver_set_override (STB_GLOBAL)
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
