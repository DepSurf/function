# Function: <code>phy_free_interrupt</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817944c0)
Location: drivers/net/phy/phy.c:843
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817944c0-ffffffff817944e7: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b8060)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817b8060-ffffffff817b8087: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81880670)
Location: drivers/net/phy/phy.c:936
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81880670-ffffffff81880699: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188d910)
Location: drivers/net/phy/phy.c:995
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff8188d910-ffffffff8188d953: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81870250)
Location: drivers/net/phy/phy.c:996
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81870250-ffffffff81870293: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81900830)
Location: drivers/net/phy/phy.c:1022
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81900830-ffffffff81900873: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a524f0)
Location: drivers/net/phy/phy.c:1054
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81a524f0-ffffffff81a5253a: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbe03)
Location: drivers/net/phy/phy.c:1083
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81bdbbd0-ffffffff81bdbc1a: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32f13)
Location: drivers/net/phy/phy.c:1317
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81c32c40-ffffffff81c32c8a: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7c03)
Location: drivers/net/phy/phy.c:1370
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff81ce7930-ffffffff81ce797a: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d0808)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffff8000109d0808-ffff8000109d0840: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab8a20)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
c0ab8a20-c0ab8a4c: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a8fc80)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
c000000000a8fc80-c000000000a8fcc4: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d4ee)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffe00061d4ee-ffffffe00061d526: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177cb30)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff8177cb30-ffffffff8177cb57: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175c8e0)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff8175c8e0-ffffffff8175c907: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817acee0)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817acee0-ffffffff817acf07: phy_free_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void phy_free_interrupt(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c6e70)
Location: drivers/net/phy/phy.c:824
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
```
**Symbols:**

```
ffffffff817c6e70-ffffffff817c6e97: phy_free_interrupt (STB_GLOBAL)
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
