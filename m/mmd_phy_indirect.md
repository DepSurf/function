# Function: <code>mmd_phy_indirect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815ea242)
Location: drivers/net/phy/phy.c:1013
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81648982)
Location: drivers/net/phy/phy.c:1110
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_write_mmd_indirect
  - drivers/net/phy/phy.c:phy_read_mmd_indirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679a62)
Location: drivers/net/phy/phy.c:1192
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_write_mmd_indirect
  - drivers/net/phy/phy.c:phy_read_mmd_indirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8168f990)
Location: drivers/net/phy/phy-core.c:12
Inline: False
```
**Symbols:**

```
ffffffff8168f990-ffffffff8168f9ea: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff816f9510)
Location: drivers/net/phy/phy-core.c:192
Inline: False
```
**Symbols:**

```
ffffffff816f9510-ffffffff816f957c: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736a00)
Location: drivers/net/phy/phy-core.c:235
Inline: False
```
**Symbols:**

```
ffffffff81736a00-ffffffff81736a5b: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759ba0)
Location: drivers/net/phy/phy-core.c:406
Inline: False
```
**Symbols:**

```
ffffffff81759ba0-ffffffff81759bfb: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796920)
Location: drivers/net/phy/phy-core.c:313
Inline: False
```
**Symbols:**

```
ffffffff81796920-ffffffff8179697b: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba3b0)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffffffff817ba3b0-ffffffff817ba40b: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818818e9)
Location: drivers/net/phy/phy-core.c:398
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81890019)
Location: drivers/net/phy/phy-core.c:445
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
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
In drivers/net/phy/phy-core.c (ffffffff81872919)
Location: drivers/net/phy/phy-core.c:445
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81903029)
Location: drivers/net/phy/phy-core.c:446
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55af1)
Location: drivers/net/phy/phy-core.c:441
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf5d1)
Location: drivers/net/phy/phy-core.c:524
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c36ebe)
Location: drivers/net/phy/phy-core.c:527
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cec489)
Location: drivers/net/phy/phy-core.c:529
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_package_read_mmd
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
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2aa0)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffff8000109d2aa0-ffff8000109d2b14: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0abab8c)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
c0abab8c-c0ababec: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a92c80)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
c000000000a92c80-c000000000a92d20: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f360)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffffffe00061f360-ffffffe00061f3cc: mmd_phy_indirect (STB_LOCAL)
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
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177ee80)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffffffff8177ee80-ffffffff8177eedb: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ec20)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffffffff8175ec20-ffffffff8175ec7b: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af230)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffffffff817af230-ffffffff817af28b: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmd_phy_indirect(struct mii_bus *bus, int phy_addr, int devad, u16 regnum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c91c0)
Location: drivers/net/phy/phy-core.c:352
Inline: False
```
**Symbols:**

```
ffffffff817c91c0-ffffffff817c921b: mmd_phy_indirect (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
