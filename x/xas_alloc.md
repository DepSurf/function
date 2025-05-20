# Function: <code>xas_alloc</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a16ef0)
Location: lib/xarray.c:345
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81a16ef0-ffffffff81a16f9b: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86a80)
Location: lib/xarray.c:354
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81a86a80-ffffffff81a86b44: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abdcf0)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81abdcf0-ffffffff81abddb4: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815f9d60)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
```
**Symbols:**

```
ffffffff815f9d60-ffffffff815f9e24: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e460)
Location: lib/xarray.c:358
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_expand
```
**Symbols:**

```
ffffffff8161e460-ffffffff8161e524: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81601da0)
Location: lib/xarray.c:358
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81601da0-ffffffff81601e64: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8166fc60)
Location: lib/xarray.c:358
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff8166fc60-ffffffff8166fd24: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178a1b0)
Location: lib/xarray.c:361
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff8178a1b0-ffffffff8178a27f: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820475f0)
Location: lib/xarray.c:361
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff820475f0-ffffffff820476bf: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c5c80)
Location: lib/xarray.c:359
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff820c5c80-ffffffff820c5d4a: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a0600)
Location: lib/xarray.c:359
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff821a0600-ffffffff821a06ca: xas_alloc (STB_LOCAL)
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
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d98d40)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffff800010d98d40-ffff800010d98e14: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e957d4)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
c0e957d4-c0e95898: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ede590)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
c000000000ede590-c000000000ede6f4: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c1a3c)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffe0008c1a3c-ffffffe0008c1ae4: xas_alloc (STB_LOCAL)
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
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5cb40)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81a5cb40-ffffffff81a5cc04: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19c20)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81a19c20-ffffffff81a19ce4: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac8f30)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81ac8f30-ffffffff81ac8ff4: xas_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xas_alloc(struct xa_state *xas, unsigned int shift);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad5410)
Location: lib/xarray.c:355
Inline: False
Direct callers:
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_create
```
**Symbols:**

```
ffffffff81ad5410-ffffffff81ad54d4: xas_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
