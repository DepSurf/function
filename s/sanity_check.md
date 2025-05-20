# Function: <code>sanity_check</code>

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
In drivers/firmware/efi/efivars.c (ffffffff816d2ed8)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In drivers/firmware/efi/efivars.c (ffffffff81736671)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
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
In drivers/firmware/efi/efivars.c (ffffffff81769ae9)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817880d9)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff817fe576)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81847b90)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81873f3d)
Location: drivers/firmware/efi/efivars.c:205
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818b8141)
Location: drivers/firmware/efi/efivars.c:149
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:282
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818eab04)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff819be23d)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff819d94c0-ffffffff819d9549: sanity_check.constprop.0 (STB_LOCAL)
ffffffff819d9a03-ffffffff819d9a5e: sanity_check.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff819bfebd)
Location: drivers/firmware/efi/efivars.c:156
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Direct callers:
  - drivers/ras/cec.c:cec_add_elem
```
**Symbols:**

```
ffffffff819d8820-ffffffff819d88a9: sanity_check.constprop.0 (STB_LOCAL)
ffffffff81c30065-ffffffff81c300c0: sanity_check.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff819a45c4)
Location: drivers/firmware/efi/efivars.c:156
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81a51874)
Location: drivers/firmware/efi/efivars.c:156
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81bc06c2)
Location: drivers/firmware/efi/efivars.c:156
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
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
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffff800010b5ddec)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (c0c3db5c)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
</details>
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
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff8188d884)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff81845204)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818df964)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efivars.c (ffffffff818fc404)
Location: drivers/firmware/efi/efivars.c:158
Inline: True
Inline callers:
  - drivers/firmware/efi/efivars.c:efivar_store_raw
  - drivers/firmware/efi/efivars.c:efivar_store_raw
```
```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:283
Inline: True
Inline callers:
  - drivers/ras/cec.c:cec_add_elem
```
</details>
</li>
</ul>

## Differences
