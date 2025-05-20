# Function: <code>efivars_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d0ed0)
Location: drivers/firmware/efi/vars.c:1141
Inline: False
```
**Symbols:**

```
ffffffff816d0ed0-ffffffff816d0f10: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817340e0)
Location: drivers/firmware/efi/vars.c:1132
Inline: False
```
**Symbols:**

```
ffffffff817340e0-ffffffff81734120: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767270)
Location: drivers/firmware/efi/vars.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81767270-ffffffff817672ed: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81785b50)
Location: drivers/firmware/efi/vars.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81785b50-ffffffff81785bcd: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fbf90)
Location: drivers/firmware/efi/vars.c:1161
Inline: False
```
**Symbols:**

```
ffffffff817fbf90-ffffffff817fc00d: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1161
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81846685-ffffffff818466b7: efivars_unregister.cold.13 (STB_LOCAL)
ffffffff818454c0-ffffffff81845519: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1218
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818728e1-ffffffff81872913: efivars_unregister.cold.13 (STB_LOCAL)
ffffffff81871610-ffffffff81871669: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818b6ac1-ffffffff818b6af4: efivars_unregister.cold (STB_LOCAL)
ffffffff818b5940-ffffffff818b599d: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818e9421-ffffffff818e9454: efivars_unregister.cold (STB_LOCAL)
ffffffff818e82a0-ffffffff818e82fd: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff819bc856-ffffffff819bc889: efivars_unregister.cold (STB_LOCAL)
ffffffff819bb970-ffffffff819bb9cd: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1187
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81c2b757-ffffffff81c2b78a: efivars_unregister.cold (STB_LOCAL)
ffffffff819bdb00-ffffffff819bdb5d: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1187
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81c1dbf0-ffffffff81c1dc23: efivars_unregister.cold (STB_LOCAL)
ffffffff819a2170-ffffffff819a21cd: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1190
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81d2f0a2-ffffffff81d2f0d5: efivars_unregister.cold (STB_LOCAL)
ffffffff81a4f0b0-ffffffff81a4f10d: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1190
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81efb544-ffffffff81efb56f: efivars_unregister.cold (STB_LOCAL)
ffffffff81bbddc0-ffffffff81bbde1f: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81d635e0)
Location: drivers/firmware/efi/vars.c:92
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81d635e0-ffffffff81d6365e: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81dce720)
Location: drivers/firmware/efi/vars.c:96
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81dce720-ffffffff81dce79e: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81e87450)
Location: drivers/firmware/efi/vars.c:104
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
  - drivers/firmware/efi/efi.c:efivars_generic_ops_unregister
```
**Symbols:**

```
ffffffff81e87450-ffffffff81e874ce: efivars_unregister (STB_GLOBAL)
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
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5b500)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffff800010b5b500-ffff800010b5b598: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3c090)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
c0c3c090-c0c3c120: efivars_unregister (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8188c1a1-ffffffff8188c1d4: efivars_unregister.cold (STB_LOCAL)
ffffffff8188b020-ffffffff8188b07d: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff81843b21-ffffffff81843b54: efivars_unregister.cold (STB_LOCAL)
ffffffff818429a0-ffffffff818429fd: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818de281-ffffffff818de2b4: efivars_unregister.cold (STB_LOCAL)
ffffffff818dd100-ffffffff818dd15d: efivars_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int efivars_unregister(struct efivars *efivars);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/firmware/efi/vars.c (0)
Location: drivers/firmware/efi/vars.c:1205
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff818fad91-ffffffff818fadc4: efivars_unregister.cold (STB_LOCAL)
ffffffff818f9c10-ffffffff818f9c6d: efivars_unregister (STB_GLOBAL)
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
