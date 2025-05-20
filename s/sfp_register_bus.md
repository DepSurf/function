# Function: <code>sfp_register_bus</code>

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
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173a730)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff8173a730-ffffffff8173a79e: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175de20)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff8175de20-ffffffff8175deaa: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179b490)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff8179b490-ffffffff8179b522: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bef40)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817bef40-ffffffff817befd2: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81887f40)
Location: drivers/net/phy/sfp-bus.c:456
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
**Symbols:**

```
ffffffff81887f40-ffffffff81887fdc: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff818961e0)
Location: drivers/net/phy/sfp-bus.c:470
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
**Symbols:**

```
ffffffff818961e0-ffffffff8189627c: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878a50)
Location: drivers/net/phy/sfp-bus.c:487
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
**Symbols:**

```
ffffffff81878a50-ffffffff81878aec: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:492
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
```
**Symbols:**

```
ffffffff81909c10-ffffffff81909cb9: sfp_register_bus (STB_LOCAL)
ffffffff81d107a8-ffffffff81d107bc: sfp_register_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:498
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
**Symbols:**

```
ffffffff81a5d2f0-ffffffff81a5d39a: sfp_register_bus (STB_LOCAL)
ffffffff81edb54e-ffffffff81edb563: sfp_register_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:447
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
**Symbols:**

```
ffffffff81be7f40-ffffffff81be7fea: sfp_register_bus (STB_LOCAL)
ffffffff8209d554-ffffffff8209d569: sfp_register_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:457
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
**Symbols:**

```
ffffffff81c402e0-ffffffff81c4038a: sfp_register_bus (STB_LOCAL)
ffffffff8211e449-ffffffff8211e45e: sfp_register_bus.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/sfp-bus.c (0)
Location: drivers/net/phy/sfp-bus.c:457
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
```
**Symbols:**

```
ffffffff81cf5910-ffffffff81cf59ba: sfp_register_bus (STB_LOCAL)
ffffffff821ffa9c-ffffffff821ffab1: sfp_register_bus.cold (STB_LOCAL)
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
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9198)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffff8000109d9198-ffff8000109d9238: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0abfe10)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
c0abfe10-c0abfec0: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9aa10)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
c000000000a9aa10-c000000000a9ab1c: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe000624304)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffe000624304-ffffffe000624374: sfp_register_bus (STB_LOCAL)
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
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81783a10)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff81783a10-ffffffff81783aa2: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81763360)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff81763360-ffffffff817633f2: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b3dc0)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817b3dc0-ffffffff817b3e52: sfp_register_bus (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sfp_register_bus(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817cdd90)
Location: drivers/net/phy/sfp-bus.c:336
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817cdd90-ffffffff817cde22: sfp_register_bus (STB_LOCAL)
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
