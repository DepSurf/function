# Function: <code>dev_alert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dev_alert(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81547860)
Location: drivers/base/core.c:2234
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81547860-ffffffff815478e3: dev_alert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dev_alert(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815995c0)
Location: drivers/base/core.c:2234
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff815995c0-ffffffff81599643: dev_alert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dev_alert(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6f00)
Location: drivers/base/core.c:2825
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff815c6f00-ffffffff815c6f83: dev_alert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dev_alert(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dbc80)
Location: drivers/base/core.c:2827
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff815dbc80-ffffffff815dbd00: dev_alert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_alert(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642cb0)
Location: drivers/base/core.c:2963
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff81642cb0-ffffffff81642d30: dev_alert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_alert(const struct device *dev, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167de10)
Location: drivers/base/core.c:3018
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:numa_node_store
  - drivers/tty/serial/serial_core.c:uart_remove_one_port
```
**Symbols:**

```
ffffffff8167de10-ffffffff8167de93: dev_alert (STB_GLOBAL)
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
</ul>
