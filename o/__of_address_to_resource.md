# Function: <code>__of_address_to_resource</code>

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
int __of_address_to_resource(struct device_node *dev, const __be32 *addrp, u64 size, unsigned int flags, const char *name, struct resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b73a20)
Location: drivers/of/address.c:777
Inline: False
Direct callers:
  - drivers/of/address.c:of_address_to_resource
  - drivers/of/address.c:of_pci_address_to_resource
```
**Symbols:**

```
ffff800010b73a20-ffff800010b73b44: __of_address_to_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __of_address_to_resource(struct device_node *dev, const __be32 *addrp, u64 size, unsigned int flags, const char *name, struct resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c55be0)
Location: drivers/of/address.c:777
Inline: False
Direct callers:
  - drivers/of/address.c:of_address_to_resource
  - drivers/of/address.c:of_pci_address_to_resource
```
**Symbols:**

```
c0c55be0-c0c55d18: __of_address_to_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __of_address_to_resource(struct device_node *dev, const __be32 *addrp, u64 size, unsigned int flags, const char *name, struct resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c503c0)
Location: drivers/of/address.c:777
Inline: False
Direct callers:
  - drivers/of/address.c:of_address_to_resource
  - drivers/of/address.c:of_pci_address_to_resource
```
**Symbols:**

```
c000000000c503c0-c000000000c50550: __of_address_to_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __of_address_to_resource(struct device_node *dev, const __be32 *addrp, u64 size, unsigned int flags, const char *name, struct resource *r);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe0007275d8)
Location: drivers/of/address.c:777
Inline: False
Direct callers:
  - drivers/of/address.c:of_address_to_resource
  - drivers/of/address.c:of_pci_address_to_resource
```
**Symbols:**

```
ffffffe0007275d8-ffffffe0007276c4: __of_address_to_resource (STB_LOCAL)
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
