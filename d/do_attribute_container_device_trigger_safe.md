# Function: <code>do_attribute_container_device_trigger_safe</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff817bf544)
Location: drivers/base/attribute_container.c:240
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff817bf3c0-ffffffff817bf4c6: do_attribute_container_device_trigger_safe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff817d4454)
Location: drivers/base/attribute_container.c:240
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff817d42d0-ffffffff817d43d6: do_attribute_container_device_trigger_safe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff817b7e64)
Location: drivers/base/attribute_container.c:240
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff817b7ce0-ffffffff817b7de6: do_attribute_container_device_trigger_safe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff818417e4)
Location: drivers/base/attribute_container.c:240
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff81841660-ffffffff81841766: do_attribute_container_device_trigger_safe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_attribute_container_device_trigger_safe(struct device *dev, struct attribute_container *cont, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81984b90)
Location: drivers/base/attribute_container.c:240
Inline: False
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff81984b90-ffffffff81984cf7: do_attribute_container_device_trigger_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_attribute_container_device_trigger_safe(struct device *dev, struct attribute_container *cont, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81af2dc0)
Location: drivers/base/attribute_container.c:240
Inline: False
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff81af2dc0-ffffffff81af2f27: do_attribute_container_device_trigger_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_attribute_container_device_trigger_safe(struct device *dev, struct attribute_container *cont, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81b40fe0)
Location: drivers/base/attribute_container.c:240
Inline: False
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff81b40fe0-ffffffff81b41147: do_attribute_container_device_trigger_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_attribute_container_device_trigger_safe(struct device *dev, struct attribute_container *cont, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81b98e80)
Location: drivers/base/attribute_container.c:240
Inline: False
Direct callers:
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
  - drivers/base/attribute_container.c:attribute_container_device_trigger_safe
```
**Symbols:**

```
ffffffff81b98e80-ffffffff81b98fe7: do_attribute_container_device_trigger_safe (STB_LOCAL)
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
