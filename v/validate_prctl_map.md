# Function: <code>validate_prctl_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81092f60)
Location: kernel/sys.c:1743
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm_map
  - kernel/sys.c:prctl_set_mm
```
**Symbols:**

```
ffffffff81092f60-ffffffff810930f3: validate_prctl_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810960f0)
Location: kernel/sys.c:1743
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810960f0-ffffffff81096282: validate_prctl_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109b0c0)
Location: kernel/sys.c:1734
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8109b0c0-ffffffff8109b246: validate_prctl_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81097ec0)
Location: kernel/sys.c:1840
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff81097ec0-ffffffff8109805e: validate_prctl_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109ebb0)
Location: kernel/sys.c:1847
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8109ebb0-ffffffff8109ed21: validate_prctl_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a4490)
Location: kernel/sys.c:1901
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810a4490-ffffffff810a45eb: validate_prctl_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ad2f0)
Location: kernel/sys.c:1902
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810ad2f0-ffffffff810ad44b: validate_prctl_map (STB_LOCAL)
```
</details>
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
</ul>
