# Function: <code>wakeup_source_free</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81712b90)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81712b90-ffffffff81712bc2: wakeup_source_free (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffffffff817ce8bc)
Location: drivers/base/power/wakeup.c:143
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff817e2f7c)
Location: drivers/base/power/wakeup.c:143
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff817c733c)
Location: drivers/base/power/wakeup.c:143
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff8185171c)
Location: drivers/base/power/wakeup.c:144
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff81997543)
Location: drivers/base/power/wakeup.c:144
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff81b08533)
Location: drivers/base/power/wakeup.c:144
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff81b56563)
Location: drivers/base/power/wakeup.c:139
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
In drivers/base/power/wakeup.c (ffffffff81baeb53)
Location: drivers/base/power/wakeup.c:139
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
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
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010903738)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffff800010903738-ffff800010903780: wakeup_source_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09edb1c)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
c09edb1c-c09edb58: wakeup_source_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a1f00)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
c0000000009a1f00-c0000000009a1f64: wakeup_source_free (STB_LOCAL)
```
</details>
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
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d8f30)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff816d8f30-ffffffff816d8f62: wakeup_source_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3550)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff816b3550-ffffffff816b3582: wakeup_source_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706850)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81706850-ffffffff81706882: wakeup_source_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_source_free(struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721260)
Location: drivers/base/power/wakeup.c:140
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_register
```
**Symbols:**

```
ffffffff81721260-ffffffff81721292: wakeup_source_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
