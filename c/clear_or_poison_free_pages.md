# Function: <code>clear_or_poison_free_pages</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1189
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff81bdfb95-ffffffff81bdfbc4: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff81113530-ffffffff8111362f: clear_or_poison_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1189
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff81bd1aa0-ffffffff81bd1acf: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff81113f10-ffffffff81113ffd: clear_or_poison_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1182
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff81caa72c-ffffffff81caa775: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff81133ff0-ffffffff811340fe: clear_or_poison_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1186
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff81e5ab5d-ffffffff81e5aba2: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff81156070-ffffffff811561e3: clear_or_poison_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1186
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff8205866b-ffffffff8205867f: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff81186600-ffffffff811867cf: clear_or_poison_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1186
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff820d6dfe-ffffffff820d6e12: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff81197770-ffffffff81197938: clear_or_poison_free_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void clear_or_poison_free_pages();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (0)
Location: kernel/power/snapshot.c:1196
Inline: False
Direct callers:
  - kernel/power/hibernate.c:create_image
```
**Symbols:**

```
ffffffff821b2095-ffffffff821b20a9: clear_or_poison_free_pages.cold (STB_LOCAL)
ffffffff811a6380-ffffffff811a65b7: clear_or_poison_free_pages (STB_GLOBAL)
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
