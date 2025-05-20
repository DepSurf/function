# Function: <code>devlink_port_attrs_pci_vf_set</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81948260)
Location: net/core/devlink.c:5851
Inline: False
```
**Symbols:**

```
ffffffff81948260-ffffffff8194829c: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197d580)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffffffff8197d580-ffffffff8197d5bc: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a51980)
Location: net/core/devlink.c:7484
Inline: False
```
**Symbols:**

```
ffffffff81a51980-ffffffff81a519bc: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a59a70)
Location: net/core/devlink.c:8356
Inline: False
```
**Symbols:**

```
ffffffff81a59a70-ffffffff81a59afe: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3d590)
Location: net/core/devlink.c:8575
Inline: False
```
**Symbols:**

```
ffffffff81a3d590-ffffffff81a3d622: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af3240)
Location: net/core/devlink.c:9318
Inline: False
```
**Symbols:**

```
ffffffff81af3240-ffffffff81af32cd: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c76fe0)
Location: net/core/devlink.c:9925
Inline: False
```
**Symbols:**

```
ffffffff81c76fe0-ffffffff81c7709f: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2f860)
Location: net/core/devlink.c:10607
Inline: False
```
**Symbols:**

```
ffffffff81e2f860-ffffffff81e2f920: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8202e7e0)
Location: net/devlink/leftover.c:7175
Inline: False
```
**Symbols:**

```
ffffffff8202e7e0-ffffffff8202e8a0: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, u32 controller, u16 pf, u16 vf, bool external);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/port.c (ffffffff82105a50)
Location: net/devlink/port.c:1356
Inline: False
```
**Symbols:**

```
ffffffff82105a50-ffffffff82105b10: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
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
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c250e8)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffff800010c250e8-ffff800010c2514c: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3c3a8)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
c0d3c3a8-c0d3c3ec: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d18db0)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
c000000000d18db0-c000000000d18e28: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079d5f0)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffffffe00079d5f0-ffffffe00079d642: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191d3f0)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffffffff8191d3f0-ffffffff8191d42c: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d71a0)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffffffff818d71a0-ffffffff818d71dc: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196e580)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffffffff8196e580-ffffffff8196e5bc: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_port_attrs_pci_vf_set(struct devlink_port *devlink_port, const unsigned char *switch_id, unsigned char switch_id_len, u16 pf, u16 vf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81990a30)
Location: net/core/devlink.c:6548
Inline: False
```
**Symbols:**

```
ffffffff81990a30-ffffffff81990a6c: devlink_port_attrs_pci_vf_set (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 controller</code>
</li>
<li>
<b>Param added. </b>
<code>bool external</code>
</li>
<li>
<b>Param removed. </b>
<code>const unsigned char *switch_id</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char switch_id_len</code>
</li>
<li>
<b>Param reordered. </b>
<code>devlink_port, switch_id, switch_id_len, pf, vf</code> ➡️ <code>devlink_port, controller, pf, vf, external</code>
</li>
</ul>
</details>
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
