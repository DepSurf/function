# Function: <code>efivar_ssdt_load</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81fe3c05)
Location: drivers/firmware/efi/efi.c:238
Inline: True
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
In drivers/firmware/efi/efi.c (ffffffff820219d4)
Location: drivers/firmware/efi/efi.c:243
Inline: True
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
In drivers/firmware/efi/efi.c (ffffffff821046e1)
Location: drivers/firmware/efi/efi.c:243
Inline: True
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
In drivers/firmware/efi/efi.c (ffffffff8270dd90)
Location: drivers/firmware/efi/efi.c:263
Inline: True
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
In drivers/firmware/efi/efi.c (ffffffff82737efb)
Location: drivers/firmware/efi/efi.c:274
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
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
In drivers/firmware/efi/efi.c (ffffffff828f1e65)
Location: drivers/firmware/efi/efi.c:278
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efivar_ssdt_load();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8290d388)
Location: drivers/firmware/efi/efi.c:278
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8290d388-ffffffff8290d515: efivar_ssdt_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efivar_ssdt_load();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82916f05)
Location: drivers/firmware/efi/efi.c:263
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff82916f05-ffffffff829170a2: efivar_ssdt_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82d29478)
Location: drivers/firmware/efi/efi.c:237
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff82d29478-ffffffff82d29605: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83017b90)
Location: drivers/firmware/efi/efi.c:241
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff83017b90-ffffffff83017d1d: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83222a68)
Location: drivers/firmware/efi/efi.c:241
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff83222a68-ffffffff83222bf5: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8330c7cc)
Location: drivers/firmware/efi/efi.c:241
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8330c7cc-ffffffff8330c959: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff834c60b5)
Location: drivers/firmware/efi/efi.c:247
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff834c60b5-ffffffff834c6246: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83f06cd0)
Location: drivers/firmware/efi/efi.c:227
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff83f06cd0-ffffffff83f06edf: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8372cd20)
Location: drivers/firmware/efi/efi.c:253
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8372cd20-ffffffff8372cf2f: efivar_ssdt_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83961100)
Location: drivers/firmware/efi/efi.c:269
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff83961100-ffffffff83961347: efivar_ssdt_load.isra.0 (STB_LOCAL)
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
In drivers/firmware/efi/efi.c (ffff8000114a5750)
Location: drivers/firmware/efi/efi.c:263
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
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
In drivers/firmware/efi/efi.c (0)
Location: drivers/firmware/efi/efi.c:318
Inline: True
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
<summary>In <code>aws</code>: ✅</summary>

```c
int efivar_ssdt_load();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828fc30b)
Location: drivers/firmware/efi/efi.c:263
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff828fc30b-ffffffff828fc4a8: efivar_ssdt_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efivar_ssdt_load();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff828f3ba7)
Location: drivers/firmware/efi/efi.c:263
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff828f3ba7-ffffffff828f3d44: efivar_ssdt_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efivar_ssdt_load();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8291153a)
Location: drivers/firmware/efi/efi.c:263
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8291153a-ffffffff829116d7: efivar_ssdt_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efivar_ssdt_load();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82917f67)
Location: drivers/firmware/efi/efi.c:263
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff82917f67-ffffffff82918104: efivar_ssdt_load (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
