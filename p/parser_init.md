# Function: <code>parser_init</code>

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
int parser_init(struct of_pci_range_parser *parser, struct device_node *node, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffff800010b72608)
Location: drivers/of/address.c:235
Inline: False
Direct callers:
  - drivers/of/address.c:of_pci_dma_range_parser_init
  - drivers/of/address.c:of_pci_range_parser_init
```
**Symbols:**

```
ffff800010b72608-ffff800010b726b4: parser_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parser_init(struct of_pci_range_parser *parser, struct device_node *node, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c0c553f0)
Location: drivers/of/address.c:235
Inline: False
Direct callers:
  - drivers/of/address.c:of_pci_dma_range_parser_init
  - drivers/of/address.c:of_pci_range_parser_init
```
**Symbols:**

```
c0c553f0-c0c5549c: parser_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parser_init(struct of_pci_range_parser *parser, struct device_node *node, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (c000000000c4f790)
Location: drivers/of/address.c:235
Inline: False
Direct callers:
  - drivers/of/address.c:of_pci_dma_range_parser_init
  - drivers/of/address.c:of_pci_range_parser_init
```
**Symbols:**

```
c000000000c4f790-c000000000c4f860: parser_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parser_init(struct of_pci_range_parser *parser, struct device_node *node, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/address.c (ffffffe0007262aa)
Location: drivers/of/address.c:235
Inline: False
Direct callers:
  - drivers/of/address.c:of_pci_dma_range_parser_init
  - drivers/of/address.c:of_pci_range_parser_init
```
**Symbols:**

```
ffffffe0007262aa-ffffffe000726312: parser_init (STB_LOCAL)
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
