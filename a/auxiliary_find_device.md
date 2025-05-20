# Function: <code>auxiliary_find_device</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff817d8b60)
Location: drivers/base/auxiliary.c:211
Inline: False
```
**Symbols:**

```
ffffffff817d8b60-ffffffff817d8b80: auxiliary_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff817bcca0)
Location: drivers/base/auxiliary.c:211
Inline: False
```
**Symbols:**

```
ffffffff817bcca0-ffffffff817bccc0: auxiliary_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81846ff0)
Location: drivers/base/auxiliary.c:209
Inline: False
```
**Symbols:**

```
ffffffff81846ff0-ffffffff81847010: auxiliary_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff8198ba20)
Location: drivers/base/auxiliary.c:352
Inline: False
```
**Symbols:**

```
ffffffff8198ba20-ffffffff8198ba4c: auxiliary_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81afb0a0)
Location: drivers/base/auxiliary.c:352
Inline: False
```
**Symbols:**

```
ffffffff81afb0a0-ffffffff81afb0cc: auxiliary_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81b49490)
Location: drivers/base/auxiliary.c:352
Inline: False
```
**Symbols:**

```
ffffffff81b49490-ffffffff81b494bc: auxiliary_find_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct auxiliary_device *auxiliary_find_device(struct device *start, const void *data, int (*match)(struct device *, const void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81ba1880)
Location: drivers/base/auxiliary.c:352
Inline: False
```
**Symbols:**

```
ffffffff81ba1880-ffffffff81ba18ac: auxiliary_find_device (STB_GLOBAL)
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
