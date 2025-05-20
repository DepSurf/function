# Function: <code>__crb_go_idle</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81660344)
Location: drivers/char/tpm/tpm_crb.c:150
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff8165fe30-ffffffff8165fe7f: __crb_go_idle.isra.9.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e9b6)
Location: drivers/char/tpm/tpm_crb.c:150
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff8167e480-ffffffff8167e4cf: __crb_go_idle.isra.9.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5567)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff816b5130-ffffffff816b516d: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
ffffffff816b57bd-ffffffff816b57d6: __crb_go_idle.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816d8247)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff816d7e10-ffffffff816d7e4d: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
ffffffff816d849d-ffffffff816d84b6: __crb_go_idle.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c383)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8178c1b0-ffffffff8178c203: __crb_go_idle (STB_LOCAL)
ffffffff8178cb2f-ffffffff8178cb48: __crb_go_idle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2913)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff817a2740-ffffffff817a2793: __crb_go_idle (STB_LOCAL)
ffffffff81c0b0f3-ffffffff81c0b10c: __crb_go_idle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81785613)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81785440-ffffffff81785495: __crb_go_idle (STB_LOCAL)
ffffffff81bfcb72-ffffffff81bfcb8b: __crb_go_idle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8180c153)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8180bf80-ffffffff8180bfd5: __crb_go_idle (STB_LOCAL)
ffffffff81cfd928-ffffffff81cfd941: __crb_go_idle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c920)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff8194c560-ffffffff8194c5bf: __crb_go_idle (STB_LOCAL)
ffffffff81ec622c-ffffffff81ec6245: __crb_go_idle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab1760)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81ab0720-ffffffff81ab0791: __crb_go_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81afd440)
Location: drivers/char/tpm/tpm_crb.c:172
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81afc690-ffffffff81afc70e: __crb_go_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __crb_go_idle(struct device *dev, struct crb_priv *priv);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81b50a50)
Location: drivers/char/tpm/tpm_crb.c:172
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
```
**Symbols:**

```
ffffffff81b4fca0-ffffffff81b4fd1e: __crb_go_idle (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3834)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffff8000108c3258-ffff8000108c32c0: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8169dc97)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff8169d860-ffffffff8169d89d: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
ffffffff8169deed-ffffffff8169df06: __crb_go_idle.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b687)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff8167b250-ffffffff8167b28d: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
ffffffff8167b8dd-ffffffff8167b8f6: __crb_go_idle.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816cbf07)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff816cbad0-ffffffff816cbb0d: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
ffffffff816cc15d-ffffffff816cc176: __crb_go_idle.isra.0.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816e63d7)
Location: drivers/char/tpm/tpm_crb.c:146
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
Direct callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
```
**Symbols:**

```
ffffffff816e5fa0-ffffffff816e5fdd: __crb_go_idle.isra.0.part.0 (STB_LOCAL)
ffffffff816e662d-ffffffff816e6646: __crb_go_idle.isra.0.part.0.cold (STB_LOCAL)
```
</details>
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
