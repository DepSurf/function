# Function: <code>__devlink_port_attrs_set</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81948124)
Location: net/core/devlink.c:5758
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff819480f0-ffffffff819481cd: __devlink_port_attrs_set (STB_LOCAL)
ffffffff819520df-ffffffff81952118: __devlink_port_attrs_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d400)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff8197d400-ffffffff8197d4ef: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a51800)
Location: net/core/devlink.c:7391
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff81a51800-ffffffff81a518ec: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59a7f)
Location: net/core/devlink.c:8283
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3d64a)
Location: net/core/devlink.c:8502
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_attrs_pci_sf_set
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af32eb)
Location: net/core/devlink.c:9245
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_attrs_pci_sf_set
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c76f3f)
Location: net/core/devlink.c:9852
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_attrs_pci_sf_set
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2f7b0)
Location: net/core/devlink.c:10534
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_port_attrs_pci_sf_set
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202e8d0)
Location: net/devlink/leftover.c:7102
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_port_attrs_pci_sf_set
  - net/devlink/leftover.c:devlink_port_attrs_pci_vf_set
  - net/devlink/leftover.c:devlink_port_attrs_pci_pf_set
  - net/devlink/leftover.c:devlink_port_attrs_set
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82105b40)
Location: net/devlink/port.c:1283
Inline: True
Inline callers:
  - net/devlink/port.c:devlink_port_attrs_pci_sf_set
  - net/devlink/port.c:devlink_port_attrs_pci_vf_set
  - net/devlink/port.c:devlink_port_attrs_pci_pf_set
  - net/devlink/port.c:devlink_port_attrs_set
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c24f40)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffff800010c24f40-ffff800010c25010: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3c250)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
c0d3c250-c0d3c31c: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d18bd0)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
c000000000d18bd0-c000000000d18cb0: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079d48a)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffe00079d48a-ffffffe00079d534: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d270)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff8191d270-ffffffff8191d35f: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d7020)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff818d7020-ffffffff818d710f: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e400)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff8196e400-ffffffff8196e4ef: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __devlink_port_attrs_set(struct devlink_port *devlink_port, enum devlink_port_flavour flavour, const unsigned char *switch_id, unsigned char switch_id_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819908b0)
Location: net/core/devlink.c:6455
Inline: True
Direct callers:
  - net/core/devlink.c:devlink_port_attrs_pci_vf_set
  - net/core/devlink.c:devlink_port_attrs_pci_pf_set
  - net/core/devlink.c:devlink_port_attrs_set
```
**Symbols:**

```
ffffffff819908b0-ffffffff8199099f: __devlink_port_attrs_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
