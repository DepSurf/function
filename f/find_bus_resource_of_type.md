# Function: <code>find_bus_resource_of_type</code>

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
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81633b80)
Location: drivers/pci/setup-bus.c:770
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff81633b80-ffffffff81633c1c: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81658c30)
Location: drivers/pci/setup-bus.c:771
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff81658c30-ffffffff81658ccc: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163b280)
Location: drivers/pci/setup-bus.c:771
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff8163b280-ffffffff8163b31c: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816abcb0)
Location: drivers/pci/setup-bus.c:771
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff816abcb0-ffffffff816abd4c: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817cf0a0)
Location: drivers/pci/setup-bus.c:771
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff817cf0a0-ffffffff817cf13c: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818eeed0)
Location: drivers/pci/setup-bus.c:771
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff818eeed0-ffffffff818eef6c: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff819323a0)
Location: drivers/pci/setup-bus.c:768
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff819323a0-ffffffff8193243c: find_bus_resource_of_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *find_bus_resource_of_type(struct pci_bus *bus, long unsigned int type_mask, long unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197aef0)
Location: drivers/pci/setup-bus.c:777
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
```
**Symbols:**

```
ffffffff8197aef0-ffffffff8197af8c: find_bus_resource_of_type (STB_LOCAL)
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
