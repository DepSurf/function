# Function: <code>clear_free_pages</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dcc50)
Location: kernel/power/snapshot.c:1135
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff810dcc50-ffffffff810dcc5b: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dbd60)
Location: kernel/power/snapshot.c:1137
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff810dbd60-ffffffff810dbd6b: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e3f80)
Location: kernel/power/snapshot.c:1139
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff810e3f80-ffffffff810e3f8b: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1139
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff810ed2da-ffffffff810ed309: clear_free_pages.cold.47 (STB_LOCAL)
ffffffff810ec210-ffffffff810ec2f3: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1140
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff810f893c-ffffffff810f896b: clear_free_pages.cold.48 (STB_LOCAL)
ffffffff810f78b0-ffffffff810f7993: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1141
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff81100f9d-ffffffff81100fe2: clear_free_pages.cold (STB_LOCAL)
ffffffff810ffe30-ffffffff810fff36: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1148
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff8110d3ea-ffffffff8110d41f: clear_free_pages.cold (STB_LOCAL)
ffffffff8110c290-ffffffff8110c39d: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1147
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff811186f8-ffffffff8111872d: clear_free_pages.cold (STB_LOCAL)
ffffffff811170b0-ffffffff811171e2: clear_free_pages (STB_GLOBAL)
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (c03bea70)
Location: kernel/power/snapshot.c:1148
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
c03bea70-c03beb7c: clear_free_pages (STB_GLOBAL)
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
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1147
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff8110560a-ffffffff8110563f: clear_free_pages.cold (STB_LOCAL)
ffffffff811044b0-ffffffff811045bd: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1148
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff810f68aa-ffffffff810f68df: clear_free_pages.cold (STB_LOCAL)
ffffffff810f5750-ffffffff810f585d: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1148
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff811038ba-ffffffff811038ef: clear_free_pages.cold (STB_LOCAL)
ffffffff81102760-ffffffff8110286d: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void clear_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1148
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
ffffffff8110ecaa-ffffffff8110ecdf: clear_free_pages.cold (STB_LOCAL)
ffffffff8110db30-ffffffff8110dc54: clear_free_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
