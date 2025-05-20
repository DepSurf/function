# Function: <code>efivars_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d0a60)
Location: drivers/firmware/efi/vars.c:1120
Inline: False
```
**Symbols:**

```
ffffffff816d0a60-ffffffff816d0a82: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81733cb0)
Location: drivers/firmware/efi/vars.c:1111
Inline: False
```
**Symbols:**

```
ffffffff81733cb0-ffffffff81733cd2: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767c30)
Location: drivers/firmware/efi/vars.c:1134
Inline: True
```
**Symbols:**

```
ffffffff81767c30-ffffffff81767c96: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817863e0)
Location: drivers/firmware/efi/vars.c:1134
Inline: True
```
**Symbols:**

```
ffffffff817863e0-ffffffff81786446: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fc840)
Location: drivers/firmware/efi/vars.c:1134
Inline: True
```
**Symbols:**

```
ffffffff817fc840-ffffffff817fc8a6: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1134
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818466b7-ffffffff818466e7: efivars_register.cold.14 (STB_LOCAL)
ffffffff81846000-ffffffff8184603d: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81872913)
Location: drivers/firmware/efi/vars.c:1191
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81872913-ffffffff81872943: efivars_register.cold.14 (STB_LOCAL)
ffffffff81872340-ffffffff8187237d: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b6af4)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818b6af4-ffffffff818b6b23: efivars_register.cold (STB_LOCAL)
ffffffff818b6560-ffffffff818b659f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e9454)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818e9454-ffffffff818e9483: efivars_register.cold (STB_LOCAL)
ffffffff818e8ec0-ffffffff818e8eff: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bc889)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff819bc889-ffffffff819bc8b8: efivars_register.cold (STB_LOCAL)
ffffffff819bc040-ffffffff819bc07f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81c2b78a)
Location: drivers/firmware/efi/vars.c:1160
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81c2b78a-ffffffff81c2b7b9: efivars_register.cold (STB_LOCAL)
ffffffff819be1d0-ffffffff819be20f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81c1dc23)
Location: drivers/firmware/efi/vars.c:1160
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81c1dc23-ffffffff81c1dc52: efivars_register.cold (STB_LOCAL)
ffffffff819a2730-ffffffff819a276f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81d2f0e9)
Location: drivers/firmware/efi/vars.c:1163
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81d2f0e9-ffffffff81d2f118: efivars_register.cold (STB_LOCAL)
ffffffff81a4f5d0-ffffffff81a4f60f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81efb584)
Location: drivers/firmware/efi/vars.c:1163
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81efb584-ffffffff81efb5b4: efivars_register.cold (STB_LOCAL)
ffffffff81bbe3b0-ffffffff81bbe3f7: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81d63550)
Location: drivers/firmware/efi/vars.c:65
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81d63550-ffffffff81d635c1: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81dce690)
Location: drivers/firmware/efi/vars.c:62
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81dce690-ffffffff81dce70f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81e87390)
Location: drivers/firmware/efi/vars.c:62
Inline: False
```
**Symbols:**

```
ffffffff81e87390-ffffffff81e87431: efivars_register (STB_GLOBAL)
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
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5c200)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffff800010b5c200-ffff800010b5c280: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3cd54)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
c0c3cd54-c0c3cdc4: efivars_register (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188c1d4)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8188c1d4-ffffffff8188c203: efivars_register.cold (STB_LOCAL)
ffffffff8188bc40-ffffffff8188bc7f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81843b54)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81843b54-ffffffff81843b83: efivars_register.cold (STB_LOCAL)
ffffffff818435c0-ffffffff818435ff: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818de2b4)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818de2b4-ffffffff818de2e3: efivars_register.cold (STB_LOCAL)
ffffffff818ddd20-ffffffff818ddd5f: efivars_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int efivars_register(struct efivars *efivars, const struct efivar_operations *ops, struct kobject *kobject);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818fadc4)
Location: drivers/firmware/efi/vars.c:1178
Inline: True
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818fadc4-ffffffff818fadf3: efivars_register.cold (STB_LOCAL)
ffffffff818fa830-ffffffff818fa86f: efivars_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct kobject *kobject</code>
</li>
</ul>
</details>
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
