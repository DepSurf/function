# Function: <code>pci_secondary_epc_epf_unlink</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_secondary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8165aa30)
Location: drivers/pci/endpoint/pci-ep-cfs.c:69
Inline: False
```
**Symbols:**

```
ffffffff8165aa30-ffffffff8165aa7a: pci_secondary_epc_epf_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_secondary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:69
Inline: False
```
**Symbols:**

```
ffffffff816cd6b0-ffffffff816cd712: pci_secondary_epc_epf_unlink (STB_LOCAL)
ffffffff81ceb0d5-ffffffff81ceb0ea: pci_secondary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_secondary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:69
Inline: False
```
**Symbols:**

```
ffffffff817f5f70-ffffffff817f5fd8: pci_secondary_epc_epf_unlink (STB_LOCAL)
ffffffff81eb251b-ffffffff81eb2530: pci_secondary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_secondary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:69
Inline: False
```
**Symbols:**

```
ffffffff81921910-ffffffff81921978: pci_secondary_epc_epf_unlink (STB_LOCAL)
ffffffff820900ee-ffffffff82090103: pci_secondary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_secondary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:70
Inline: False
```
**Symbols:**

```
ffffffff819652f0-ffffffff81965358: pci_secondary_epc_epf_unlink (STB_LOCAL)
ffffffff82110495-ffffffff821104aa: pci_secondary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_secondary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:70
Inline: False
```
**Symbols:**

```
ffffffff819ae9a0-ffffffff819aea08: pci_secondary_epc_epf_unlink (STB_LOCAL)
ffffffff821ee1bd-ffffffff821ee1d2: pci_secondary_epc_epf_unlink.cold (STB_LOCAL)
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
