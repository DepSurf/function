# Function: <code>xbc_exit</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xbc_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a1a8f)
Location: lib/bootconfig.c:907
Inline: False
Direct callers:
  - init/main.c:kernel_init
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff834a1a8f-ffffffff834a1af0: xbc_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xbc_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83edb317)
Location: lib/bootconfig.c:907
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff83edb4b0-ffffffff83edb517: xbc_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xbc_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83700e47)
Location: lib/bootconfig.c:907
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff83700fe0-ffffffff83701047: xbc_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xbc_exit();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83934687)
Location: lib/bootconfig.c:907
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
Direct callers:
  - init/main.c:kernel_init
```
**Symbols:**

```
ffffffff83934820-ffffffff83934887: xbc_exit (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
