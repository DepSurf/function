# Function: <code>xas_create</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a180c0)
Location: lib/xarray.c:619
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81a180c0-ffffffff81a1843a: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a87c90)
Location: lib/xarray.c:634
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81a87c90-ffffffff81a8805e: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abef30)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81abef30-ffffffff81abf2fe: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb2a0)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff815fb2a0-ffffffff815fb48a: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161fe10)
Location: lib/xarray.c:638
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff8161fe10-ffffffff8161fffa: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603590)
Location: lib/xarray.c:638
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81603590-ffffffff8160375f: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:638
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81671a20-ffffffff81671cc1: xas_create (STB_LOCAL)
ffffffff81cdffdf-ffffffff81ce0005: xas_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178bbc0)
Location: lib/xarray.c:641
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff8178bbc0-ffffffff8178bdbe: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049110)
Location: lib/xarray.c:641
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff82049110-ffffffff8204930e: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c79e0)
Location: lib/xarray.c:639
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff820c79e0-ffffffff820c7bce: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a2360)
Location: lib/xarray.c:639
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff821a2360-ffffffff821a254e: xas_create (STB_LOCAL)
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
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9a128)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffff800010d9a128-ffff800010d9a520: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96f08)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
c0e96f08-c0e97278: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee0530)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
c000000000ee0530-c000000000ee0b30: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c1ae4)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffe0008c1ae4-ffffffe0008c1dc0: xas_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5dd80)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81a5dd80-ffffffff81a5e14e: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1ae50)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81a1ae50-ffffffff81a1b21e: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81aca170)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81aca170-ffffffff81aca53e: xas_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_create(struct xa_state *xas, bool allow_root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6740)
Location: lib/xarray.c:635
Inline: False
Direct callers:
  - lib/xarray.c:xa_store_range
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
```
**Symbols:**

```
ffffffff81ad6740-ffffffff81ad6b0e: xas_create (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
