# Function: <code>klp_shadow_get</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81102e91)
Location: kernel/livepatch/shadow.c:95
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81102e30-ffffffff81102e79: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8110b465)
Location: kernel/livepatch/shadow.c:95
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff8110b410-ffffffff8110b459: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81116c55)
Location: kernel/livepatch/shadow.c:95
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81116c00-ffffffff81116c49: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81120ef0)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81120ef0-ffffffff81120f38: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8112d510)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff8112d510-ffffffff8112d558: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8113bc70)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff8113bc70-ffffffff8113bcb8: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81136390)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81136390-ffffffff811363eb: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81137190)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81137190-ffffffff811371eb: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81159e40)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81159e40-ffffffff81159e9b: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811836a7)
Location: kernel/livepatch/shadow.c:83
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81183470-ffffffff811834ec: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811be857)
Location: kernel/livepatch/shadow.c:83
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff811be5e0-ffffffff811be65c: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811d1287)
Location: kernel/livepatch/shadow.c:83
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff811d1010-ffffffff811d108c: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811e5f07)
Location: kernel/livepatch/shadow.c:83
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff811e5c90-ffffffff811e5d0c: klp_shadow_get (STB_GLOBAL)
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
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (c0000000001f1fe0)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
c0000000001f1fe0-c0000000001f2068: klp_shadow_get (STB_GLOBAL)
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
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81125af0)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81125af0-ffffffff81125b38: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81118550)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81118550-ffffffff81118598: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811239e0)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff811239e0-ffffffff81123a28: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *klp_shadow_get(void *obj, long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81130000)
Location: kernel/livepatch/shadow.c:83
Inline: False
Direct callers:
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
**Symbols:**

```
ffffffff81130000-ffffffff8113006c: klp_shadow_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
