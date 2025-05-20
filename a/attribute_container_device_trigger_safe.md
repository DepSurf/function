# Function: <code>attribute_container_device_trigger_safe</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff817bf4d0)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff817bf4d0-ffffffff817bf5f1: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff817d43e0)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff817d43e0-ffffffff817d4501: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff817b7df0)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff817b7df0-ffffffff817b7f11: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81841770)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff81841770-ffffffff81841891: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81984da0)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff81984da0-ffffffff81984e85: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81af2ff0)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff81af2ff0-ffffffff81af30d5: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81b41210)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff81b41210-ffffffff81b412f5: attribute_container_device_trigger_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int attribute_container_device_trigger_safe(struct device *dev, int (*fn)(struct attribute_container *, struct device *, struct device *), int (*undo)(struct attribute_container *, struct device *, struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/attribute_container.c (ffffffff81b990b0)
Location: drivers/base/attribute_container.c:297
Inline: False
Direct callers:
  - drivers/base/transport_class.c:transport_add_device
```
**Symbols:**

```
ffffffff81b990b0-ffffffff81b99195: attribute_container_device_trigger_safe (STB_GLOBAL)
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
