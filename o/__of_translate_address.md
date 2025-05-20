# Function: <code>__of_translate_address</code>

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
u64 __of_translate_address(struct device_node *dev, struct device_node * (*get_parent)(const struct device_node *), const __be32 *in_addr, const char *rprop, struct device_node **host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b733d0)
Location: drivers/of/address.c:571
Inline: False
Direct callers:
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_translate_dma_address
  - drivers/of/address.c:of_translate_address
```
**Symbols:**

```
ffff800010b733d0-ffff800010b7398c: __of_translate_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 __of_translate_address(struct device_node *dev, struct device_node * (*get_parent)(const struct device_node *), const __be32 *in_addr, const char *rprop, struct device_node **host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c5554c)
Location: drivers/of/address.c:571
Inline: False
Direct callers:
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_translate_dma_address
  - drivers/of/address.c:of_translate_address
```
**Symbols:**

```
c0c5554c-c0c55b50: __of_translate_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 __of_translate_address(struct device_node *dev, struct device_node * (*get_parent)(const struct device_node *), const __be32 *in_addr, const char *rprop, struct device_node **host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4fb80)
Location: drivers/of/address.c:571
Inline: False
Direct callers:
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_translate_dma_address
  - drivers/of/address.c:of_translate_address
```
**Symbols:**

```
c000000000c4fb80-c000000000c50320: __of_translate_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 __of_translate_address(struct device_node *dev, struct device_node * (*get_parent)(const struct device_node *), const __be32 *in_addr, const char *rprop, struct device_node **host);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe00072702c)
Location: drivers/of/address.c:571
Inline: False
Direct callers:
  - drivers/of/address.c:__of_address_to_resource
  - drivers/of/address.c:of_translate_dma_address
  - drivers/of/address.c:of_translate_address
```
**Symbols:**

```
ffffffe00072702c-ffffffe000727574: __of_translate_address (STB_LOCAL)
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
