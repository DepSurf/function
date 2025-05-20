# Function: <code>phy_copy_pause_bits</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817973a5)
Location: drivers/net/phy/phy_device.c:2063
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817baed5)
Location: drivers/net/phy/phy_device.c:2032
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy_device.c (ffffffff818852a5)
Location: drivers/net/phy/phy_device.c:2517
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy_device.c (ffffffff81893b55)
Location: drivers/net/phy/phy_device.c:2567
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy_device.c (ffffffff818766a4)
Location: drivers/net/phy/phy_device.c:2613
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy_device.c (ffffffff819072b4)
Location: drivers/net/phy/phy_device.c:2659
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
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
In drivers/net/phy/phy_device.c (ffffffff81a59404)
Location: drivers/net/phy/phy_device.c:2687
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be4020)
Location: drivers/net/phy/phy_device.c:2693
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
```
**Symbols:**

```
ffffffff81be4020-ffffffff81be4067: phy_copy_pause_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3bb30)
Location: drivers/net/phy/phy_device.c:2740
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
```
**Symbols:**

```
ffffffff81c3bb30-ffffffff81c3bb77: phy_copy_pause_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf0f30)
Location: drivers/net/phy/phy_device.c:2747
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_remove_link_mode
```
**Symbols:**

```
ffffffff81cf0f30-ffffffff81cf0f77: phy_copy_pause_bits (STB_LOCAL)
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
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d5c88)
Location: drivers/net/phy/phy_device.c:2032
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
**Symbols:**

```
ffff8000109d5c88-ffff8000109d5ce4: phy_copy_pause_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abd6b4)
Location: drivers/net/phy/phy_device.c:2032
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
**Symbols:**

```
c0abd6b4-c0abd6f8: phy_copy_pause_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a969f0)
Location: drivers/net/phy/phy_device.c:2032
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
**Symbols:**

```
c000000000a969f0-c000000000a96a58: phy_copy_pause_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_copy_pause_bits(long unsigned int *dst, long unsigned int *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000621fda)
Location: drivers/net/phy/phy_device.c:2032
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
**Symbols:**

```
ffffffe000621fda-ffffffe00062204e: phy_copy_pause_bits (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8177f9a5)
Location: drivers/net/phy/phy_device.c:2032
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175f745)
Location: drivers/net/phy/phy_device.c:2032
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817afd55)
Location: drivers/net/phy/phy_device.c:2032
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817c9ce5)
Location: drivers/net/phy/phy_device.c:2032
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_support_asym_pause
  - drivers/net/phy/phy_device.c:phy_support_sym_pause
  - drivers/net/phy/phy_device.c:phy_advertise_supported
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
