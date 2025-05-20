# Function: <code>sfp_upstream_stop</code>

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
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173a870)
Location: drivers/net/phy/sfp-bus.c:429
Inline: False
```
**Symbols:**

```
ffffffff8173a870-ffffffff8173a89b: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175dfa0)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff8175dfa0-ffffffff8175dfcb: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179b620)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff8179b620-ffffffff8179b64b: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bf0d0)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff817bf0d0-ffffffff817bf0fb: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff818880d0)
Location: drivers/net/phy/sfp-bus.c:553
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff818880d0-ffffffff818880fe: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81896370)
Location: drivers/net/phy/sfp-bus.c:567
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81896370-ffffffff8189639e: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878c00)
Location: drivers/net/phy/sfp-bus.c:604
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81878c00-ffffffff81878c2e: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:609
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81d107fb-ffffffff81d10810: sfp_upstream_stop.cold (STB_LOCAL)
ffffffff81909da0-ffffffff81909dde: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:615
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81edb5a2-ffffffff81edb5b7: sfp_upstream_stop.cold (STB_LOCAL)
ffffffff81a5d4a0-ffffffff81a5d4e8: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:564
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff8209d5a8-ffffffff8209d5bd: sfp_upstream_stop.cold (STB_LOCAL)
ffffffff81be8120-ffffffff81be8168: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff8211e49d-ffffffff8211e4b2: sfp_upstream_stop.cold (STB_LOCAL)
ffffffff81c404c0-ffffffff81c40508: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:574
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff821ffaf0-ffffffff821ffb05: sfp_upstream_stop.cold (STB_LOCAL)
ffffffff81cf5af0-ffffffff81cf5b38: sfp_upstream_stop (STB_GLOBAL)
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
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d93a0)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffff8000109d93a0-ffff8000109d93e0: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0abffe8)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
c0abffe8-c0ac0028: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9ad60)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
c000000000a9ad60-c000000000a9adc8: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe000624476)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffe000624476-ffffffe0006244a8: sfp_upstream_stop (STB_GLOBAL)
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
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81783ba0)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff81783ba0-ffffffff81783bcb: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817634f0)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff817634f0-ffffffff8176351b: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b3f50)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff817b3f50-ffffffff817b3f7b: sfp_upstream_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sfp_upstream_stop(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817cdf20)
Location: drivers/net/phy/sfp-bus.c:433
Inline: False
```
**Symbols:**

```
ffffffff817cdf20-ffffffff817cdf4b: sfp_upstream_stop (STB_GLOBAL)
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
