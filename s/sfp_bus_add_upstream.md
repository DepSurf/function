# Function: <code>sfp_bus_add_upstream</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81888dc0)
Location: drivers/net/phy/sfp-bus.c:627
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81888dc0-ffffffff81888ed6: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81897080)
Location: drivers/net/phy/sfp-bus.c:641
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81897080-ffffffff81897196: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81879970)
Location: drivers/net/phy/sfp-bus.c:678
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81879970-ffffffff81879a82: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8190a7d0)
Location: drivers/net/phy/sfp-bus.c:688
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff8190a7d0-ffffffff8190a8e2: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5e1d0)
Location: drivers/net/phy/sfp-bus.c:694
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81a5e1d0-ffffffff81a5e2d2: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be8f10)
Location: drivers/net/phy/sfp-bus.c:643
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81be8f10-ffffffff81be9012: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81c41340)
Location: drivers/net/phy/sfp-bus.c:673
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81c41340-ffffffff81c41442: sfp_bus_add_upstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sfp_bus_add_upstream(struct sfp_bus *bus, void *upstream, const struct sfp_upstream_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81cf69b0)
Location: drivers/net/phy/sfp-bus.c:673
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81cf69b0-ffffffff81cf6ab2: sfp_bus_add_upstream (STB_GLOBAL)
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
