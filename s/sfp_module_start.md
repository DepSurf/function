# Function: <code>sfp_module_start</code>

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
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81888230)
Location: drivers/net/phy/sfp-bus.c:747
Inline: False
```
**Symbols:**

```
ffffffff81888230-ffffffff8188825f: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff818964d0)
Location: drivers/net/phy/sfp-bus.c:761
Inline: False
```
**Symbols:**

```
ffffffff818964d0-ffffffff818964ff: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878d60)
Location: drivers/net/phy/sfp-bus.c:798
Inline: False
```
**Symbols:**

```
ffffffff81878d60-ffffffff81878d8f: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:808
Inline: False
```
**Symbols:**

```
ffffffff81d1089b-ffffffff81d108b0: sfp_module_start.cold (STB_LOCAL)
ffffffff8190aa30-ffffffff8190aa76: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:814
Inline: False
```
**Symbols:**

```
ffffffff81edb663-ffffffff81edb678: sfp_module_start.cold (STB_LOCAL)
ffffffff81a5e120-ffffffff81a5e170: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:764
Inline: False
```
**Symbols:**

```
ffffffff8209d611-ffffffff8209d626: sfp_module_start.cold (STB_LOCAL)
ffffffff81be8db0-ffffffff81be8e00: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:794
Inline: False
```
**Symbols:**

```
ffffffff8211e51b-ffffffff8211e530: sfp_module_start.cold (STB_LOCAL)
ffffffff81c411e0-ffffffff81c41230: sfp_module_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sfp_module_start(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:794
Inline: False
```
**Symbols:**

```
ffffffff821ffb6e-ffffffff821ffb83: sfp_module_start.cold (STB_LOCAL)
ffffffff81cf6850-ffffffff81cf68a0: sfp_module_start (STB_GLOBAL)
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
