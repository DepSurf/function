# Function: <code>__klp_shadow_get_or_alloc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, void *data, size_t size, gfp_t gfp_flags, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81102e80)
Location: kernel/livepatch/shadow.c:116
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81102e80-ffffffff81103029: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8110b460)
Location: kernel/livepatch/shadow.c:116
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff8110b460-ffffffff8110b66f: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81116c50)
Location: kernel/livepatch/shadow.c:116
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81116c50-ffffffff81116e5f: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81120f40)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81120f40-ffffffff811210d4: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8112d560)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff8112d560-ffffffff8112d6f4: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8113bce0)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff8113bce0-ffffffff8113be74: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811363f0)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff811363f0-ffffffff81136584: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811371f0)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff811371f0-ffffffff8113737c: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81159ea0)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81159ea0-ffffffff8115a02e: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81183690)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81183690-ffffffff81183942: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811be840)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff811be840-ffffffff811beaf2: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811d1270)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff811d1270-ffffffff811d152c: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811e5ef0)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff811e5ef0-ffffffff811e61ac: __klp_shadow_get_or_alloc (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (c0000000001f2070)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
c0000000001f2070-c0000000001f22f8: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81125b40)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81125b40-ffffffff81125cd4: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811185a0)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff811185a0-ffffffff81118734: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81123a30)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81123a30-ffffffff81123bc4: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data, bool warn_on_exist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81130070)
Location: kernel/livepatch/shadow.c:104
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_alloc
```
**Symbols:**

```
ffffffff81130070-ffffffff81130204: __klp_shadow_get_or_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>klp_shadow_ctor_t ctor</code>
</li>
<li>
<b>Param added. </b>
<code>void *ctor_data</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param reordered. </b>
<code>obj, id, data, size, gfp_flags, warn_on_exist</code> ➡️ <code>obj, id, size, gfp_flags, ctor, ctor_data, warn_on_exist</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
