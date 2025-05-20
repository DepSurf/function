# Function: <code>faraday_pci_read_config</code>

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
int faraday_pci_read_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (ffff80001071f1a0)
Location: drivers/pci/controller/pci-ftpci100.c:210
Inline: False
```
**Symbols:**

```
ffff80001071f1a0-ffff80001071f2c4: faraday_pci_read_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int faraday_pci_read_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (c08a7b04)
Location: drivers/pci/controller/pci-ftpci100.c:210
Inline: False
```
**Symbols:**

```
c08a7b04-c08a7c0c: faraday_pci_read_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int faraday_pci_read_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (c000000000890960)
Location: drivers/pci/controller/pci-ftpci100.c:210
Inline: False
```
**Symbols:**

```
c000000000890960-c000000000890b28: faraday_pci_read_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int faraday_pci_read_config(struct pci_bus *bus, unsigned int fn, int config, int size, u32 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/pci-ftpci100.c (ffffffe0004e5e44)
Location: drivers/pci/controller/pci-ftpci100.c:210
Inline: False
```
**Symbols:**

```
ffffffe0004e5e44-ffffffe0004e5f72: faraday_pci_read_config (STB_LOCAL)
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
