# Function: <code>faraday_pci_write_config</code>

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
int faraday_pci_write_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071ee80)
Location: drivers/pci/controller/pci-ftpci100.c:252
Inline: False
```
**Symbols:**

```
ffff80001071ee80-ffff80001071eff0: faraday_pci_write_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int faraday_pci_write_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (c08a7e88)
Location: drivers/pci/controller/pci-ftpci100.c:252
Inline: False
```
**Symbols:**

```
c08a7e88-c08a7fd8: faraday_pci_write_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int faraday_pci_write_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (c000000000890760)
Location: drivers/pci/controller/pci-ftpci100.c:252
Inline: False
```
**Symbols:**

```
c000000000890760-c00000000089095c: faraday_pci_write_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int faraday_pci_write_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e607e)
Location: drivers/pci/controller/pci-ftpci100.c:252
Inline: False
```
**Symbols:**

```
ffffffe0004e607e-ffffffe0004e6114: faraday_pci_write_config (STB_LOCAL)
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
