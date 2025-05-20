# Function: <code>ghes_edac_unregister</code>

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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:69
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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:69
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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:69
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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:75
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff817d3af0)
Location: drivers/edac/ghes_edac.c:518
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
  - drivers/acpi/apei/ghes.c:ghes_probe
```
**Symbols:**

```
ffffffff817d3af0-ffffffff817d3b1c: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff8181c7f0)
Location: drivers/edac/ghes_edac.c:528
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff8181c7f0-ffffffff8181c822: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81848160)
Location: drivers/edac/ghes_edac.c:551
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff81848160-ffffffff81848192: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff8188afd0)
Location: drivers/edac/ghes_edac.c:549
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff8188afd0-ffffffff8188b005: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff818bd020)
Location: drivers/edac/ghes_edac.c:584
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff818bd020-ffffffff818bd0d2: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff8198d680)
Location: drivers/edac/ghes_edac.c:565
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff8198d680-ffffffff8198d742: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81991340)
Location: drivers/edac/ghes_edac.c:641
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff81991340-ffffffff8199141e: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff819758b0)
Location: drivers/edac/ghes_edac.c:641
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff819758b0-ffffffff8197598e: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:641
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff81d2afe4-ffffffff81d2aff8: ghes_edac_unregister.cold (STB_LOCAL)
ffffffff81a1e5c0-ffffffff81a1e6af: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:520
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff81ef7180-ffffffff81ef7194: ghes_edac_unregister.cold (STB_LOCAL)
ffffffff81b86d30-ffffffff81b86e33: ghes_edac_unregister (STB_GLOBAL)
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
In drivers/edac/ghes_edac.c (ffffffff842b2d0a)
Location: drivers/edac/ghes_edac.c:507
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
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
In drivers/edac/ghes_edac.c (ffffffff83af5a1a)
Location: drivers/edac/ghes_edac.c:507
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
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
In drivers/edac/ghes_edac.c (ffffffff83d517da)
Location: drivers/edac/ghes_edac.c:507
Inline: True
Inline callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
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
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffff800010b15508)
Location: drivers/edac/ghes_edac.c:584
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffff800010b15508-ffff800010b15614: ghes_edac_unregister (STB_GLOBAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff818b24d0)
Location: drivers/edac/ghes_edac.c:584
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff818b24d0-ffffffff818b2582: ghes_edac_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ghes_edac_unregister(struct ghes *ghes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff818ce780)
Location: drivers/edac/ghes_edac.c:584
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_remove
```
**Symbols:**

```
ffffffff818ce780-ffffffff818ce832: ghes_edac_unregister (STB_GLOBAL)
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
