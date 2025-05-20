# Function: <code>fs_lookup_key</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (ffffffff8130b060)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff8130b060-ffffffff8130b0ab: fs_lookup_key.isra.0 (STB_LOCAL)
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
In fs/fs_parser.c (ffffffff8131e030)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff8131e030-ffffffff8131e07b: fs_lookup_key.isra.0 (STB_LOCAL)
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
In fs/fs_parser.c (ffffffff81357e27)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff81364877)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff8136b2d7)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff813b9f97)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff8143fad8)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff814ce828)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff81504a88)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffffffff81539748)
Location: fs/fs_parser.c:54
Inline: True
Inline callers:
  - fs/fs_parser.c:__fs_parse
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
In fs/fs_parser.c (ffff8000103d6290)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffff8000103d6290-ffff8000103d62e8: fs_lookup_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct fs_parameter_spec *fs_lookup_key(const struct fs_parameter_description *desc, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c05afcdc)
Location: fs/fs_parser.c:45
Inline: False
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
c05afcdc-c05afd4c: fs_lookup_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (c0000000004d9c00)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
c0000000004d9c00-c0000000004d9e20: fs_lookup_key.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (ffffffe00028ffde)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffe00028ffde-ffffffe000290024: fs_lookup_key.isra.0 (STB_LOCAL)
```
</details>
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
In fs/fs_parser.c (ffffffff81316610)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81316610-ffffffff8131665b: fs_lookup_key.isra.0 (STB_LOCAL)
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
In fs/fs_parser.c (ffffffff81307200)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81307200-ffffffff8130724b: fs_lookup_key.isra.0 (STB_LOCAL)
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
In fs/fs_parser.c (ffffffff81314400)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81314400-ffffffff8131444b: fs_lookup_key.isra.0 (STB_LOCAL)
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
In fs/fs_parser.c (ffffffff81325c50)
Location: fs/fs_parser.c:45
Inline: True
Direct callers:
  - fs/fs_parser.c:fs_parse
  - fs/fs_parser.c:fs_parse
```
**Symbols:**

```
ffffffff81325c50-ffffffff81325c9b: fs_lookup_key.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
