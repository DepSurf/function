# Function: <code>module_init_section</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81166300)
Location: kernel/module.c:2810
Inline: False
Direct callers:
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
**Symbols:**

```
ffffffff81166300-ffffffff81166326: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162a30)
Location: kernel/module.c:2897
Inline: False
Direct callers:
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
**Symbols:**

```
ffffffff81162a30-ffffffff81162a56: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811634e0)
Location: kernel/module.c:2821
Inline: False
Direct callers:
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
**Symbols:**

```
ffffffff811634e0-ffffffff81163501: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81188a30)
Location: kernel/module.c:2843
Inline: False
Direct callers:
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
**Symbols:**

```
ffffffff81188a30-ffffffff81188a51: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118e870)
Location: kernel/module/main.c:1616
Inline: False
Direct callers:
  - kernel/module/main.c:layout_sections
  - kernel/module/main.c:layout_sections
```
**Symbols:**

```
ffffffff8118e870-ffffffff8118e89b: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cb270)
Location: kernel/module/main.c:1614
Inline: False
Direct callers:
  - kernel/module/main.c:layout_sections
  - kernel/module/main.c:layout_sections
```
**Symbols:**

```
ffffffff811cb270-ffffffff811cb29b: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811de820)
Location: kernel/module/main.c:1612
Inline: False
Direct callers:
  - kernel/module/main.c:__layout_sections
```
**Symbols:**

```
ffffffff811de820-ffffffff811de84b: module_init_section (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool module_init_section(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f4550)
Location: kernel/module/main.c:1620
Inline: False
Direct callers:
  - kernel/module/main.c:__layout_sections
```
**Symbols:**

```
ffffffff811f4550-ffffffff811f457b: module_init_section (STB_WEAK)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
