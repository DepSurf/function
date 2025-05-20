# Function: <code>copy_fdtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8122a0c7)
Location: fs/file.c:89
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252817)
Location: fs/file.c:90
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81265a8b)
Location: fs/file.c:90
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812731c6)
Location: fs/file.c:75
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295af6)
Location: fs/file.c:76
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bbe17)
Location: fs/file.c:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d1007)
Location: fs/file.c:71
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ee038)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ffaf8)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81338bd1)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_fdtable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344651)
Location: fs/file.c:76
Inline: True
Inline callers:
  - fs/file.c:expand_fdtable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8134aac5)
Location: fs/file.c:76
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81398885)
Location: fs/file.c:76
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_fdtable(struct fdtable *nfdt, struct fdtable *ofdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8141aa10)
Location: fs/file.c:76
Inline: False
Direct callers:
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff8141aa10-ffffffff8141aa8b: copy_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_fdtable(struct fdtable *nfdt, struct fdtable *ofdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814a68a0)
Location: fs/file.c:76
Inline: False
Direct callers:
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff814a68a0-ffffffff814a691b: copy_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_fdtable(struct fdtable *nfdt, struct fdtable *ofdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff814db860)
Location: fs/file.c:76
Inline: False
Direct callers:
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff814db860-ffffffff814db8db: copy_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_fdtable(struct fdtable *nfdt, struct fdtable *ofdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff8150df90)
Location: fs/file.c:76
Inline: False
Direct callers:
  - fs/file.c:expand_files
```
**Symbols:**

```
ffffffff8150df90-ffffffff8150e00b: copy_fdtable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b15ec)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590688)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ac8c0)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe0002756f4)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f80d8)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e8cf8)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f5ee8)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81307006)
Location: fs/file.c:71
Inline: True
Inline callers:
  - fs/file.c:expand_files
```
</details>
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
