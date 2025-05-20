# Function: <code>__devlink_port_type_set</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:5674
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff8194d310-ffffffff8194d381: __devlink_port_type_set (STB_LOCAL)
ffffffff8195237f-ffffffff81952392: __devlink_port_type_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81982c70)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81982c70-ffffffff81982cdd: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ad10)
Location: net/core/devlink.c:7307
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81a5ad10-ffffffff81a5ad7d: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a66650)
Location: net/core/devlink.c:8187
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81a66650-ffffffff81a666c2: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a46ba0)
Location: net/core/devlink.c:8406
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81a46ba0-ffffffff81a46c12: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81b019a0)
Location: net/core/devlink.c:9149
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81b019a0-ffffffff81b01a13: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c80fc0)
Location: net/core/devlink.c:9756
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81c80fc0-ffffffff81c81049: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:10393
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_netdevice_event
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81e3e060-ffffffff81e3e357: __devlink_port_type_set (STB_LOCAL)
ffffffff820ad2af-ffffffff820ad2c4: __devlink_port_type_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:6962
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_port_netdevice_event
  - net/devlink/leftover.c:devlink_port_type_clear
  - net/devlink/leftover.c:devlink_port_type_ib_set
  - net/devlink/leftover.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff8203dc40-ffffffff8203df3f: __devlink_port_type_set (STB_LOCAL)
ffffffff821365b1-ffffffff821365c6: __devlink_port_type_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/port.c (0)
Location: net/devlink/port.c:1143
Inline: False
Direct callers:
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_netdevice_event
  - net/devlink/port.c:devlink_port_type_clear
  - net/devlink/port.c:devlink_port_type_ib_set
  - net/devlink/port.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff821074c0-ffffffff821077cf: __devlink_port_type_set (STB_LOCAL)
ffffffff8221809c-ffffffff822180b1: __devlink_port_type_set.cold (STB_LOCAL)
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
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2ad90)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffff800010c2ad90-ffff800010c2ae84: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d421d4)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
c0d421d4-c0d4225c: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d20330)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
c000000000d20330-c000000000d203dc: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a23ac)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffe0007a23ac-ffffffe0007a2436: __devlink_port_type_set (STB_LOCAL)
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
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81922ae0)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81922ae0-ffffffff81922b4d: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dc890)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff818dc890-ffffffff818dc8fd: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81973c70)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81973c70-ffffffff81973cdd: __devlink_port_type_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __devlink_port_type_set(struct devlink_port *devlink_port, enum devlink_port_type type, void *type_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81996160)
Location: net/core/devlink.c:6371
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_port_type_clear
  - net/core/devlink.c:devlink_port_type_ib_set
  - net/core/devlink.c:devlink_port_type_eth_set
```
**Symbols:**

```
ffffffff81996160-ffffffff819961cd: __devlink_port_type_set (STB_LOCAL)
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
