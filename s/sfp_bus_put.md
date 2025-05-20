# Function: <code>sfp_bus_put</code>

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
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8173adb0)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff8173adb0-ffffffff8173ae0b: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8175e600)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff8175e600-ffffffff8175e65b: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8179bc70)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff8179bc70-ffffffff8179bccf: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817bf720)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817bf720-ffffffff817bf77f: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81888d53)
Location: drivers/net/phy/sfp-bus.c:449
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81888c00-ffffffff81888c6d: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81897013)
Location: drivers/net/phy/sfp-bus.c:463
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81896ec0-ffffffff81896f2d: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81879903)
Location: drivers/net/phy/sfp-bus.c:480
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff818797b0-ffffffff8187981d: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff8190a763)
Location: drivers/net/phy/sfp-bus.c:485
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff8190a610-ffffffff8190a67d: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5deee)
Location: drivers/net/phy/sfp-bus.c:491
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81a5dd60-ffffffff81a5ddec: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81be8b8e)
Location: drivers/net/phy/sfp-bus.c:440
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81be89e0-ffffffff81be8a6c: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81c40fbe)
Location: drivers/net/phy/sfp-bus.c:450
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81c40e10-ffffffff81c40e9c: sfp_bus_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81cf662e)
Location: drivers/net/phy/sfp-bus.c:450
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
  - drivers/net/phy/sfp-bus.c:sfp_bus_add_upstream
Direct callers:
  - drivers/net/phy/phy_device.c:phy_sfp_probe
```
**Symbols:**

```
ffffffff81cf6480-ffffffff81cf650c: sfp_bus_put (STB_GLOBAL)
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
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffff8000109d9ba0)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffff8000109d9ba0-ffff8000109d9c10: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c0ac07b0)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
c0ac07b0-c0ac0814: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (c000000000a9b6c0)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
c000000000a9b6c0-c000000000a9b774: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffe000624a88)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffe000624a88-ffffffe000624aea: sfp_bus_put (STB_LOCAL)
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
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817841f0)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817841f0-ffffffff8178424f: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81763b40)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff81763b40-ffffffff81763b9f: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817b45a0)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817b45a0-ffffffff817b45ff: sfp_bus_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sfp_bus_put(struct sfp_bus *bus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff817ce570)
Location: drivers/net/phy/sfp-bus.c:331
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_unregister_socket
  - drivers/net/phy/sfp-bus.c:sfp_register_socket
  - drivers/net/phy/sfp-bus.c:sfp_unregister_upstream
  - drivers/net/phy/sfp-bus.c:sfp_register_upstream
```
**Symbols:**

```
ffffffff817ce570-ffffffff817ce5cf: sfp_bus_put (STB_LOCAL)
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
