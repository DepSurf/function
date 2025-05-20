# Function: <code>device_find_child_by_name</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d5c40)
Location: drivers/base/core.c:2552
Inline: False
```
**Symbols:**

```
ffffffff816d5c40-ffffffff816d5ce6: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9a30)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffffffff816f9a30-ffffffff816f9ad6: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2970)
Location: drivers/base/core.c:3090
Inline: False
```
**Symbols:**

```
ffffffff817b2970-ffffffff817b2a16: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7470)
Location: drivers/base/core.c:3502
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff817c7470-ffffffff817c7516: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa8e0)
Location: drivers/base/core.c:3729
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff817aa8e0-ffffffff817aa986: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833aa0)
Location: drivers/base/core.c:3794
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81833aa0-ffffffff81833b46: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975270)
Location: drivers/base/core.c:3828
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81975270-ffffffff8197532b: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae0a60)
Location: drivers/base/core.c:4027
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81ae0a60-ffffffff81ae0b1b: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2ec80)
Location: drivers/base/core.c:4036
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81b2ec80-ffffffff81b2ed3b: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b86480)
Location: drivers/base/core.c:4049
Inline: False
Direct callers:
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81b86480-ffffffff81b8653b: device_find_child_by_name (STB_GLOBAL)
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
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e3ea0)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffff8000108e3ea0-ffff8000108e3f5c: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d29dc)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
c09d29dc-c09d2a9c: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979050)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
c000000000979050-c000000000979320: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000578f58)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffffffe000578f58-ffffffe000578fde: device_find_child_by_name (STB_GLOBAL)
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
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf220)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffffffff816bf220-ffffffff816bf2c6: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a4d0)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffffffff8169a4d0-ffffffff8169a576: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ed6f0)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffffffff816ed6f0-ffffffff816ed796: device_find_child_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *device_find_child_by_name(struct device *parent, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81707f30)
Location: drivers/base/core.c:2589
Inline: False
```
**Symbols:**

```
ffffffff81707f30-ffffffff81707fd6: device_find_child_by_name (STB_GLOBAL)
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
