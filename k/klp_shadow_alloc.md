# Function: <code>klp_shadow_alloc</code>

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
void *klp_shadow_alloc(void *obj, long unsigned int id, void *data, size_t size, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81103030)
Location: kernel/livepatch/shadow.c:189
Inline: False
```
**Symbols:**

```
ffffffff81103030-ffffffff81103046: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8110b670)
Location: kernel/livepatch/shadow.c:208
Inline: False
```
**Symbols:**

```
ffffffff8110b670-ffffffff8110b682: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81116e60)
Location: kernel/livepatch/shadow.c:208
Inline: False
```
**Symbols:**

```
ffffffff81116e60-ffffffff81116e72: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811210e0)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff811210e0-ffffffff811210f2: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8112d700)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff8112d700-ffffffff8112d712: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8113be80)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff8113be80-ffffffff8113be92: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81136590)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81136590-ffffffff811365a2: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81137380)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81137380-ffffffff81137392: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8115a030)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff8115a030-ffffffff8115a042: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81183950)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81183950-ffffffff81183974: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811beb10)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff811beb10-ffffffff811beb34: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811d1540)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff811d1540-ffffffff811d1564: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811e61c0)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff811e61c0-ffffffff811e61e4: klp_shadow_alloc (STB_GLOBAL)
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
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (c0000000001f2300)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
c0000000001f2300-c0000000001f2318: klp_shadow_alloc (STB_GLOBAL)
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
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81125ce0)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81125ce0-ffffffff81125cf2: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81118740)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81118740-ffffffff81118752: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81123bd0)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81123bd0-ffffffff81123be2: klp_shadow_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *klp_shadow_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81130210)
Location: kernel/livepatch/shadow.c:196
Inline: False
```
**Symbols:**

```
ffffffff81130210-ffffffff81130222: klp_shadow_alloc (STB_GLOBAL)
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
<code>obj, id, data, size, gfp_flags</code> ➡️ <code>obj, id, size, gfp_flags, ctor, ctor_data</code>
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
