# Function: <code>refcount_add_not_zero_checked</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff814e20a0)
Location: lib/refcount.c:61
Inline: True
```
**Symbols:**

```
ffffffff814e20a0-ffffffff814e210e: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8150df40)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffff8150df40-ffffffff8150dfa6: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff8152bd90)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffff8152bd90-ffffffff8152bdf6: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffff800010637ba8)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffff800010637ba8-ffff800010637c64: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c07dd45c)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
c07dd45c-c07dd510: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (c0000000007dd7c0)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
c0000000007dd7c0-c0000000007dd8b8: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffe0004649fc)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffe0004649fc-ffffffe000464a82: refcount_add_not_zero_checked (STB_GLOBAL)
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
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81524370)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffff81524370-ffffffff815243d6: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81514650)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffff81514650-ffffffff815146b6: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81520400)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffff81520400-ffffffff81520466: refcount_add_not_zero_checked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool refcount_add_not_zero_checked(unsigned int i, refcount_t *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/refcount.c (ffffffff81539d80)
Location: lib/refcount.c:64
Inline: True
Direct callers:
  - lib/refcount.c:refcount_add_checked
```
**Symbols:**

```
ffffffff81539d80-ffffffff81539de6: refcount_add_not_zero_checked (STB_GLOBAL)
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
