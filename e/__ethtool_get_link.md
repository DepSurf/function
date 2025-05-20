# Function: <code>__ethtool_get_link</code>

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
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a85610)
Location: net/ethtool/common.c:307
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81a85610-ffffffff81a85652: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a8efa0)
Location: net/ethtool/common.c:334
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81a8efa0-ffffffff81a8efe2: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81a786a0)
Location: net/ethtool/common.c:487
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81a786a0-ffffffff81a786e2: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81b32790)
Location: net/ethtool/common.c:489
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81b32790-ffffffff81b327d2: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81cbdd00)
Location: net/ethtool/common.c:493
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81cbdd00-ffffffff81cbdd50: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81e7c4f0)
Location: net/ethtool/common.c:508
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81e7c4f0-ffffffff81e7c540: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81ed8890)
Location: net/ethtool/common.c:516
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81ed8890-ffffffff81ed88e0: __ethtool_get_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ethtool_get_link(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/common.c (ffffffff81f9c6a0)
Location: net/ethtool/common.c:516
Inline: False
Direct callers:
  - net/ethtool/ioctl.c:__dev_ethtool
  - net/ethtool/linkstate.c:linkstate_prepare_data
```
**Symbols:**

```
ffffffff81f9c6a0-ffffffff81f9c6f3: __ethtool_get_link (STB_GLOBAL)
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
