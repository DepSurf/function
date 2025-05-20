# Function: <code>wakeup_source_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155b830)
Location: drivers/base/power/wakeup.c:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff8155b830-ffffffff8155b86d: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815adb32)
Location: drivers/base/power/wakeup.c:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff815adab0-ffffffff815adaed: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dc902)
Location: drivers/base/power/wakeup.c:76
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff815dc880-ffffffff815dc8bd: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f13f0)
Location: drivers/base/power/wakeup.c:78
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff815f13f0-ffffffff815f1433: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816589e0)
Location: drivers/base/power/wakeup.c:78
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff816589e0-ffffffff81658a23: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694a10)
Location: drivers/base/power/wakeup.c:83
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff81694a10-ffffffff81694a53: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b50a0)
Location: drivers/base/power/wakeup.c:83
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff816b50a0-ffffffff816b50e3: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_source_prepare(struct wakeup_source *ws, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816eea90)
Location: drivers/base/power/wakeup.c:83
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
**Symbols:**

```
ffffffff816eea90-ffffffff816eead3: wakeup_source_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
</ul>
