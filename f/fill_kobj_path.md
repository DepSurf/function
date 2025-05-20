# Function: <code>fill_kobj_path</code>

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
In lib/kobject.c (ffffffff813eb583)
Location: lib/kobject.c:121
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff814318d3)
Location: lib/kobject.c:121
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff8144db43)
Location: lib/kobject.c:121
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff818ede07)
Location: lib/kobject.c:121
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81974027)
Location: lib/kobject.c:121
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff819d0577)
Location: lib/kobject.c:138
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81a09ad7)
Location: lib/kobject.c:138
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81a799e6)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81ab0d46)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fill_kobj_path(struct kobject *kobj, char *path, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815ea820)
Location: lib/kobject.c:147
Inline: False
Direct callers:
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff815ea820-ffffffff815ea8b1: fill_kobj_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fill_kobj_path(struct kobject *kobj, char *path, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f140)
Location: lib/kobject.c:147
Inline: False
Direct callers:
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff8160f140-ffffffff8160f1d1: fill_kobj_path (STB_LOCAL)
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
In lib/kobject.c (ffffffff815f2927)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff8165fb07)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fill_kobj_path(struct kobject *kobj, char *path, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779530)
Location: lib/kobject.c:115
Inline: False
Direct callers:
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff81779530-ffffffff817795e6: fill_kobj_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fill_kobj_path(const struct kobject *kobj, char *path, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022510)
Location: lib/kobject.c:115
Inline: False
Direct callers:
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff82022510-ffffffff820225d1: fill_kobj_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fill_kobj_path(const struct kobject *kobj, char *path, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2570)
Location: lib/kobject.c:117
Inline: False
Direct callers:
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff820a2570-ffffffff820a2631: fill_kobj_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fill_kobj_path(const struct kobject *kobj, char *path, int length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a5f0)
Location: lib/kobject.c:124
Inline: False
Direct callers:
  - lib/kobject.c:kobject_get_path
```
**Symbols:**

```
ffffffff8217a5f0-ffffffff8217a6b1: fill_kobj_path (STB_LOCAL)
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
In lib/kobject.c (ffff800010d8a750)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (c0e85430)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (c000000000ecc274)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffe0008b3d86)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81a4fb96)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81a0cc96)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81abbf86)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
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
In lib/kobject.c (ffffffff81ac8406)
Location: lib/kobject.c:147
Inline: True
Inline callers:
  - lib/kobject.c:kobject_get_path
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject *kobj</code> ➡️ <code>const struct kobject *kobj</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
