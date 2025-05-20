# Function: <code>xennet_xdp_set</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff818a814c)
Location: drivers/net/xen-netfront.c:1437
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_xdp
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
In drivers/net/xen-netfront.c (ffffffff8188b670)
Location: drivers/net/xen-netfront.c:1435
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1580
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff8191e5f0-ffffffff8191e7c1: xennet_xdp_set.constprop.0 (STB_LOCAL)
ffffffff81d113c0-ffffffff81d11402: xennet_xdp_set.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1617
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff81a73990-ffffffff81a73b7d: xennet_xdp_set.constprop.0 (STB_LOCAL)
ffffffff81edc12a-ffffffff81edc16c: xennet_xdp_set.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1617
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff81c05de0-ffffffff81c06003: xennet_xdp_set.constprop.0 (STB_LOCAL)
ffffffff8209db2b-ffffffff8209db40: xennet_xdp_set.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1617
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff81c6b4d0-ffffffff81c6b6f1: xennet_xdp_set.isra.0 (STB_LOCAL)
ffffffff8211f0b3-ffffffff8211f0c8: xennet_xdp_set.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/xen-netfront.c (0)
Location: drivers/net/xen-netfront.c:1618
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff81d1feb0-ffffffff81d200c2: xennet_xdp_set.isra.0 (STB_LOCAL)
ffffffff82200889-ffffffff8220089e: xennet_xdp_set.isra.0.cold (STB_LOCAL)
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
