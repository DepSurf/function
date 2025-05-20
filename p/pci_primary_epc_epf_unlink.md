# Function: <code>pci_primary_epc_epf_unlink</code>

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
void pci_primary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff8165a9e0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:130
Inline: False
```
**Symbols:**

```
ffffffff8165a9e0-ffffffff8165aa27: pci_primary_epc_epf_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_primary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:130
Inline: False
```
**Symbols:**

```
ffffffff816cd650-ffffffff816cd6af: pci_primary_epc_epf_unlink (STB_LOCAL)
ffffffff81ceb0c0-ffffffff81ceb0d5: pci_primary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_primary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:130
Inline: False
```
**Symbols:**

```
ffffffff817f5f00-ffffffff817f5f65: pci_primary_epc_epf_unlink (STB_LOCAL)
ffffffff81eb2506-ffffffff81eb251b: pci_primary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pci_primary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:130
Inline: False
```
**Symbols:**

```
ffffffff81921890-ffffffff819218f5: pci_primary_epc_epf_unlink (STB_LOCAL)
ffffffff820900d9-ffffffff820900ee: pci_primary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pci_primary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:131
Inline: False
```
**Symbols:**

```
ffffffff81965270-ffffffff819652d5: pci_primary_epc_epf_unlink (STB_LOCAL)
ffffffff82110480-ffffffff82110495: pci_primary_epc_epf_unlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pci_primary_epc_epf_unlink(struct config_item *epc_item, struct config_item *epf_item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:131
Inline: False
```
**Symbols:**

```
ffffffff819ae920-ffffffff819ae985: pci_primary_epc_epf_unlink (STB_LOCAL)
ffffffff821ee1a8-ffffffff821ee1bd: pci_primary_epc_epf_unlink.cold (STB_LOCAL)
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
