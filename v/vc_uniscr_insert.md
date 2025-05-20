# Function: <code>vc_uniscr_insert</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81645ad8)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167a058)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff8169c848)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff8174de58)
Location: drivers/tty/vt/vt.c:391
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff81769419)
Location: drivers/tty/vt/vt.c:384
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff8174d009)
Location: drivers/tty/vt/vt.c:384
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff817cefd9)
Location: drivers/tty/vt/vt.c:380
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff8190d129)
Location: drivers/tty/vt/vt.c:380
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vc_uniscr_insert(struct vc_data *vc, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a66ca0)
Location: drivers/tty/vt/vt.c:380
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:insert_char
```
**Symbols:**

```
ffffffff81a66ca0-ffffffff81a66d1d: vc_uniscr_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vc_uniscr_insert(struct vc_data *vc, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab14c0)
Location: drivers/tty/vt/vt.c:368
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:insert_char
```
**Symbols:**

```
ffffffff81ab14c0-ffffffff81ab153d: vc_uniscr_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vc_uniscr_insert(struct vc_data *vc, unsigned int nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b04120)
Location: drivers/tty/vt/vt.c:367
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:insert_char
```
**Symbols:**

```
ffffffff81b04120-ffffffff81b0419d: vc_uniscr_insert (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff8000108740b0)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (c0976e98)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009122d8)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000543e4c)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff816622a8)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff81642628)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff81690688)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
In drivers/tty/vt/vt.c (ffffffff816aac78)
Location: drivers/tty/vt/vt.c:385
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
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
