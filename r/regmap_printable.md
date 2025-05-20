# Function: <code>regmap_printable</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff815edbaa)
Location: drivers/base/regmap/regmap-debugfs.c:80
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff81601d6d)
Location: drivers/base/regmap/regmap-debugfs.c:80
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff8166a11d)
Location: drivers/base/regmap/regmap-debugfs.c:80
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff816a5a5c)
Location: drivers/base/regmap/regmap-debugfs.c:85
Inline: True
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff816c659c)
Location: drivers/base/regmap/regmap-debugfs.c:85
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817015a0)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffff817015a0-ffffffff817015e8: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff817258f0)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffff817258f0-ffffffff81725938: regmap_printable (STB_LOCAL)
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff817e2416)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff817f6e09)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff817db585)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff818671a5)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff819af521)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff81b234c1)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff81b735cc)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
In drivers/base/regmap/regmap-debugfs.c (ffffffff81bc73ec)
Location: drivers/base/regmap/regmap-debugfs.c:80
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
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
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffff80001091a6f8)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffff80001091a6f8-ffff80001091a768: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (c0a00240)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
c0a00240-c0a00294: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (c0000000009be960)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
c0000000009be960-c0000000009bea00: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffe00059a77c)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffe00059a77c-ffffffe00059a7d8: regmap_printable (STB_LOCAL)
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
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff816ebc20)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffff816ebc20-ffffffff816ebc68: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff816c6260)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffff816c6260-ffffffff816c62a8: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff81718db0)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffff81718db0-ffffffff81718df8: regmap_printable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool regmap_printable(struct regmap *map, unsigned int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-debugfs.c (ffffffff81734110)
Location: drivers/base/regmap/regmap-debugfs.c:81
Inline: True
Direct callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_read_debugfs
```
**Symbols:**

```
ffffffff81734110-ffffffff81734158: regmap_printable (STB_LOCAL)
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
