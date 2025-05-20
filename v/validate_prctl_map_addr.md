# Function: <code>validate_prctl_map_addr</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2b30)
Location: kernel/sys.c:1905
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b2b30-ffffffff810b2c42: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b9120)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b9120-ffffffff810b9232: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0d80)
Location: kernel/sys.c:1911
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810c0d80-ffffffff810c0eb5: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bbee0)
Location: kernel/sys.c:1912
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810bbee0-ffffffff810bc015: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd780)
Location: kernel/sys.c:1929
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810bd780-ffffffff810bd89e: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d0190)
Location: kernel/sys.c:1907
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810d0190-ffffffff810d02c0: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e6b90)
Location: kernel/sys.c:1919
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810e6b90-ffffffff810e6cd6: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110aa00)
Location: kernel/sys.c:1924
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff8110aa00-ffffffff8110ab46: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81116bc0)
Location: kernel/sys.c:1942
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff81116bc0-ffffffff81116d06: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811205b0)
Location: kernel/sys.c:1955
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff811205b0-ffffffff811206f6: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101145c8)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffff8000101145c8-ffff8000101146fc: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036ad28)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
c036ad28-c036ae4c: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015d340)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
c00000000015d340-c00000000015d4c8: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d22b8)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffe0000d22b8-ffffffe0000d2394: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b3490)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b3490-ffffffff810b35a2: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a1dc0)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810a1dc0-ffffffff810a1ed2: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b29f0)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810b29f0-ffffffff810b2b02: validate_prctl_map_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int validate_prctl_map_addr(struct prctl_mm_map *prctl_map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810baff0)
Location: kernel/sys.c:1895
Inline: True
Direct callers:
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm
  - kernel/sys.c:prctl_set_mm_map
```
**Symbols:**

```
ffffffff810baff0-ffffffff810bb102: validate_prctl_map_addr (STB_LOCAL)
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
