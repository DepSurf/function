# Function: <code>hpc_get_adapter_speed</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e080)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff8153e080-ffffffff8153e1e1: hpc_get_adapter_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff81555430)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff81555430-ffffffff815555b7: hpc_get_adapter_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff81585530-ffffffff8158562d: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8158609f-ffffffff81586109: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff815a6f10-ffffffff815a700d: hpc_get_adapter_speed (STB_LOCAL)
ffffffff815a7a7f-ffffffff815a7ae9: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff8164fc20-ffffffff8164fd1d: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8165074f-ffffffff816507b9: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff816730c0-ffffffff816731bd: hpc_get_adapter_speed (STB_LOCAL)
ffffffff81bfd079-ffffffff81bfd0e3: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:439
Inline: False
```
**Symbols:**

```
ffffffff816555c0-ffffffff816556e0: hpc_get_adapter_speed (STB_LOCAL)
ffffffff81beef57-ffffffff81beefb6: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:439
Inline: False
```
**Symbols:**

```
ffffffff816c7490-ffffffff816c75db: hpc_get_adapter_speed (STB_LOCAL)
ffffffff81ce9fda-ffffffff81cea074: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:439
Inline: False
```
**Symbols:**

```
ffffffff817ed4b0-ffffffff817ed60a: hpc_get_adapter_speed (STB_LOCAL)
ffffffff81eb1097-ffffffff81eb1131: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:439
Inline: False
```
**Symbols:**

```
ffffffff81914740-ffffffff81914925: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8208fbdd-ffffffff8208fc14: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:439
Inline: False
```
**Symbols:**

```
ffffffff81957d70-ffffffff81957f41: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8210ff39-ffffffff8210ff70: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:439
Inline: False
```
**Symbols:**

```
ffffffff819a12e0-ffffffff819a14b1: hpc_get_adapter_speed (STB_LOCAL)
ffffffff821edc61-ffffffff821edc98: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710598)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffff800010710598-ffff800010710740: hpc_get_adapter_speed (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dbda6)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffe0004dbda6-ffffffe0004dbeec: hpc_get_adapter_speed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff8159a720-ffffffff8159a81d: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8159b28f-ffffffff8159b2f9: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff815898b0-ffffffff815899ad: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8158a41f-ffffffff8158a489: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff8159ac60-ffffffff8159ad5d: hpc_get_adapter_speed (STB_LOCAL)
ffffffff8159b7cf-ffffffff8159b839: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hpc_get_adapter_speed(struct slot *slot, enum pci_bus_speed *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:444
Inline: False
```
**Symbols:**

```
ffffffff815b50a0-ffffffff815b519d: hpc_get_adapter_speed (STB_LOCAL)
ffffffff815b5bff-ffffffff815b5c69: hpc_get_adapter_speed.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
