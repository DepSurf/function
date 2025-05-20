# Function: <code>auxiliary_device_init</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81c0e699)
Location: drivers/base/auxiliary.c:135
Inline: True
```
**Symbols:**

```
ffffffff81c0e699-ffffffff81c0e6e1: auxiliary_device_init.cold (STB_LOCAL)
ffffffff817d8c50-ffffffff817d8c83: auxiliary_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81c00aac)
Location: drivers/base/auxiliary.c:135
Inline: True
```
**Symbols:**

```
ffffffff81c00aac-ffffffff81c00af4: auxiliary_device_init.cold (STB_LOCAL)
ffffffff817bcdc0-ffffffff817bcdf3: auxiliary_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81d03536)
Location: drivers/base/auxiliary.c:133
Inline: True
```
**Symbols:**

```
ffffffff81d03536-ffffffff81d0357e: auxiliary_device_init.cold (STB_LOCAL)
ffffffff81847110-ffffffff81847143: auxiliary_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:274
Inline: False
```
**Symbols:**

```
ffffffff81ecbc1b-ffffffff81ecbc5b: auxiliary_device_init.cold (STB_LOCAL)
ffffffff8198b740-ffffffff8198b77d: auxiliary_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81afaca0)
Location: drivers/base/auxiliary.c:274
Inline: False
```
**Symbols:**

```
ffffffff81afaca0-ffffffff81afad1c: auxiliary_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81b49090)
Location: drivers/base/auxiliary.c:274
Inline: False
```
**Symbols:**

```
ffffffff81b49090-ffffffff81b4910c: auxiliary_device_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int auxiliary_device_init(struct auxiliary_device *auxdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81ba1480)
Location: drivers/base/auxiliary.c:274
Inline: False
```
**Symbols:**

```
ffffffff81ba1480-ffffffff81ba14fc: auxiliary_device_init (STB_GLOBAL)
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
