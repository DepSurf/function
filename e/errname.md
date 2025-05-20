# Function: <code>errname</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff815de410)
Location: lib/errname.c:216
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815de410-ffffffff815de454: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff815fba90)
Location: lib/errname.c:217
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815fba90-ffffffff815fbad4: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff815de6e0)
Location: lib/errname.c:217
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815de6e0-ffffffff815de722: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff8164a190)
Location: lib/errname.c:217
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8164a190-ffffffff8164a20a: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff817608c0)
Location: lib/errname.c:217
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff817608c0-ffffffff8176094e: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff8188f3d0)
Location: lib/errname.c:223
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8188f3d0-ffffffff8188f45e: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff818d1810)
Location: lib/errname.c:223
Inline: False
Direct callers:
  - rust/helpers.c:rust_helper_errname
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818d1810-ffffffff818d189e: errname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *errname(int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/errname.c (ffffffff81923800)
Location: lib/errname.c:217
Inline: False
Direct callers:
  - rust/helpers.c:rust_helper_errname
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81923800-ffffffff8192388e: errname (STB_GLOBAL)
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
