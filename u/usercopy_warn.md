# Function: <code>usercopy_warn</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812918d0)
Location: mm/usercopy.c:73
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812918d0-ffffffff81291968: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812a68f0)
Location: mm/usercopy.c:75
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812a68f0-ffffffff812a6988: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812c1fd0)
Location: mm/usercopy.c:71
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812c1fd0-ffffffff812c2068: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812d3f00)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812d3f00-ffffffff812d3f98: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81309c70)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff81309c70-ffffffff81309d05: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81315a90)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff81315a90-ffffffff81315b25: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff8131bc80)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff8131bc80-ffffffff8131bd15: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/usercopy.c (0)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff81cc3599-ffffffff81cc35cb: usercopy_warn.cold (STB_LOCAL)
ffffffff81368f40-ffffffff81368ff6: usercopy_warn (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffff800010379e60)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffff800010379e60-ffff800010379f58: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (c0565068)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
c0565068-c056515c: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (c00000000046d260)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
c00000000046d260-c00000000046d354: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffe000251106)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffe000251106-ffffffe0002511c2: usercopy_warn (STB_GLOBAL)
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
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812cc4e0)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812cc4e0-ffffffff812cc578: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812bd350)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812bd350-ffffffff812bd3e8: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812ca2f0)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812ca2f0-ffffffff812ca388: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usercopy_warn(const char *name, const char *detail, bool to_user, long unsigned int offset, long unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff812daff0)
Location: mm/usercopy.c:72
Inline: False
Direct callers:
  - mm/slub.c:__check_heap_object
```
**Symbols:**

```
ffffffff812daff0-ffffffff812db088: usercopy_warn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
