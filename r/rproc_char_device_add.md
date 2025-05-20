# Function: <code>rproc_char_device_add</code>

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
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:96
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81c2f109-ffffffff81c2f127: rproc_char_device_add.cold (STB_LOCAL)
ffffffff819cd440-ffffffff819cd4c2: rproc_char_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:109
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81c213ce-ffffffff81c213ec: rproc_char_device_add.cold (STB_LOCAL)
ffffffff819b26c0-ffffffff819b2742: rproc_char_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:109
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81d32e5c-ffffffff81d32e7a: rproc_char_device_add.cold (STB_LOCAL)
ffffffff81a60e80-ffffffff81a60f02: rproc_char_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (0)
Location: drivers/remoteproc/remoteproc_cdev.c:98
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81eff2b5-ffffffff81eff2d3: rproc_char_device_add.cold (STB_LOCAL)
ffffffff81bd1420-ffffffff81bd14ac: rproc_char_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff81d7cdd0)
Location: drivers/remoteproc/remoteproc_cdev.c:98
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81d7cdd0-ffffffff81d7ce86: rproc_char_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff81deafa0)
Location: drivers/remoteproc/remoteproc_cdev.c:98
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81deafa0-ffffffff81deb056: rproc_char_device_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rproc_char_device_add(struct rproc *rproc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_cdev.c (ffffffff81ea1210)
Location: drivers/remoteproc/remoteproc_cdev.c:98
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_add
```
**Symbols:**

```
ffffffff81ea1210-ffffffff81ea12c6: rproc_char_device_add (STB_GLOBAL)
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
