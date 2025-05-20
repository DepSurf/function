# Function: <code>wwan_create_port</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct wwan_port *wwan_create_port(struct device *parent, enum wwan_port_type type, const struct wwan_port_ops *ops, void *drvdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff818880b0)
Location: drivers/net/wwan/wwan_core.c:213
Inline: True
```
**Symbols:**

```
ffffffff818880b0-ffffffff81888396: wwan_create_port.part.0 (STB_LOCAL)
ffffffff818883a0-ffffffff818883c2: wwan_create_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct wwan_port *wwan_create_port(struct device *parent, enum wwan_port_type type, const struct wwan_port_ops *ops, void *drvdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff8191a4e0)
Location: drivers/net/wwan/wwan_core.c:355
Inline: True
```
**Symbols:**

```
ffffffff8191a4e0-ffffffff8191a6fc: wwan_create_port.part.0 (STB_LOCAL)
ffffffff8191a700-ffffffff8191a722: wwan_create_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct wwan_port *wwan_create_port(struct device *parent, enum wwan_port_type type, const struct wwan_port_ops *ops, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81a6f830)
Location: drivers/net/wwan/wwan_core.c:421
Inline: False
```
**Symbols:**

```
ffffffff81a6f830-ffffffff81a6fa82: wwan_create_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct wwan_port *wwan_create_port(struct device *parent, enum wwan_port_type type, const struct wwan_port_ops *ops, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c02670)
Location: drivers/net/wwan/wwan_core.c:426
Inline: False
```
**Symbols:**

```
ffffffff81c02670-ffffffff81c028c2: wwan_create_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct wwan_port *wwan_create_port(struct device *parent, enum wwan_port_type type, const struct wwan_port_ops *ops, struct wwan_port_caps *caps, void *drvdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c67bd0)
Location: drivers/net/wwan/wwan_core.c:430
Inline: False
```
**Symbols:**

```
ffffffff81c67bd0-ffffffff81c67e77: wwan_create_port (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wwan_port_caps *caps</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, type, ops, drvdata</code> ➡️ <code>parent, type, ops, caps, drvdata</code>
</li>
</ul>
</details>
</li>
</ul>
