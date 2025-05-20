# Function: <code>no_hash_pointers_enable</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int no_hash_pointers_enable(char *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff832056b7)
Location: lib/vsprintf.c:2215
Inline: False
```
**Symbols:**

```
ffffffff832056b7-ffffffff83205772: no_hash_pointers_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int no_hash_pointers_enable(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff832ed3e0)
Location: lib/vsprintf.c:2232
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff832ed3e0-ffffffff832ed4b0: no_hash_pointers_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int no_hash_pointers_enable(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff834a5179)
Location: lib/vsprintf.c:2224
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff834a5179-ffffffff834a5251: no_hash_pointers_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int no_hash_pointers_enable(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff83f1c490)
Location: lib/vsprintf.c:2225
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff83f1c490-ffffffff83f1c575: no_hash_pointers_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int no_hash_pointers_enable(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff83742d20)
Location: lib/vsprintf.c:2246
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff83742d20-ffffffff83742e05: no_hash_pointers_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int no_hash_pointers_enable(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff83977810)
Location: lib/vsprintf.c:2253
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_init
```
**Symbols:**

```
ffffffff83977810-ffffffff839778f5: no_hash_pointers_enable (STB_GLOBAL)
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
