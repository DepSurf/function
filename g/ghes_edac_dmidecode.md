# Function: <code>ghes_edac_dmidecode</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff817d2770)
Location: drivers/edac/ghes_edac.c:84
Inline: False
```
**Symbols:**

```
ffffffff817d2770-ffffffff817d2987: ghes_edac_dmidecode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:84
Inline: False
```
**Symbols:**

```
ffffffff8181b560-ffffffff8181b769: ghes_edac_dmidecode (STB_LOCAL)
ffffffff8181c822-ffffffff8181c841: ghes_edac_dmidecode.cold.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:96
Inline: False
```
**Symbols:**

```
ffffffff81846d50-ffffffff81846f94: ghes_edac_dmidecode (STB_LOCAL)
ffffffff81848192-ffffffff818481b1: ghes_edac_dmidecode.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:94
Inline: False
```
**Symbols:**

```
ffffffff81889b10-ffffffff81889d54: ghes_edac_dmidecode (STB_LOCAL)
ffffffff8188b005-ffffffff8188b026: ghes_edac_dmidecode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:102
Inline: False
```
**Symbols:**

```
ffffffff818bbac0-ffffffff818bbd04: ghes_edac_dmidecode (STB_LOCAL)
ffffffff818bd0d2-ffffffff818bd0f3: ghes_edac_dmidecode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:102
Inline: False
```
**Symbols:**

```
ffffffff8198c370-ffffffff8198c5b1: ghes_edac_dmidecode (STB_LOCAL)
ffffffff8198d742-ffffffff8198d75e: ghes_edac_dmidecode.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffff800010b14490)
Location: drivers/edac/ghes_edac.c:102
Inline: False
```
**Symbols:**

```
ffff800010b14490-ffff800010b146e8: ghes_edac_dmidecode (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:102
Inline: False
```
**Symbols:**

```
ffffffff818b0f70-ffffffff818b11b4: ghes_edac_dmidecode (STB_LOCAL)
ffffffff818b2582-ffffffff818b25a3: ghes_edac_dmidecode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ghes_edac_dmidecode(const struct dmi_header *dh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:102
Inline: False
```
**Symbols:**

```
ffffffff818cd200-ffffffff818cd444: ghes_edac_dmidecode (STB_LOCAL)
ffffffff818ce832-ffffffff818ce853: ghes_edac_dmidecode.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
