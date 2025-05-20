# Function: <code>__auxiliary_device_add</code>

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
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:174
Inline: False
```
**Symbols:**

```
ffffffff81c0e64b-ffffffff81c0e699: __auxiliary_device_add.cold (STB_LOCAL)
ffffffff817d8b00-ffffffff817d8b56: __auxiliary_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:174
Inline: False
```
**Symbols:**

```
ffffffff81c00a5e-ffffffff81c00aac: __auxiliary_device_add.cold (STB_LOCAL)
ffffffff817bcc40-ffffffff817bcc96: __auxiliary_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:172
Inline: False
```
**Symbols:**

```
ffffffff81d034e8-ffffffff81d03536: __auxiliary_device_add.cold (STB_LOCAL)
ffffffff81846f90-ffffffff81846fe6: __auxiliary_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:313
Inline: False
```
**Symbols:**

```
ffffffff81ecbc8f-ffffffff81ecbcdd: __auxiliary_device_add.cold (STB_LOCAL)
ffffffff8198b9b0-ffffffff8198ba14: __auxiliary_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81afafd0)
Location: drivers/base/auxiliary.c:313
Inline: False
```
**Symbols:**

```
ffffffff81afafd0-ffffffff81afb090: __auxiliary_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81b493c0)
Location: drivers/base/auxiliary.c:313
Inline: False
```
**Symbols:**

```
ffffffff81b493c0-ffffffff81b49480: __auxiliary_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __auxiliary_device_add(struct auxiliary_device *auxdev, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81ba17b0)
Location: drivers/base/auxiliary.c:313
Inline: False
```
**Symbols:**

```
ffffffff81ba17b0-ffffffff81ba1870: __auxiliary_device_add (STB_GLOBAL)
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
