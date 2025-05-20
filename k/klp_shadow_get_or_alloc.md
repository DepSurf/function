# Function: <code>klp_shadow_get_or_alloc</code>

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
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, void *data, size_t size, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81103050)
Location: kernel/livepatch/shadow.c:215
Inline: False
```
**Symbols:**

```
ffffffff81103050-ffffffff81103063: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8110b690)
Location: kernel/livepatch/shadow.c:237
Inline: False
```
**Symbols:**

```
ffffffff8110b690-ffffffff8110b6a2: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81116e80)
Location: kernel/livepatch/shadow.c:237
Inline: False
```
**Symbols:**

```
ffffffff81116e80-ffffffff81116e92: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81121100)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff81121100-ffffffff81121112: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8112d720)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff8112d720-ffffffff8112d732: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8113bea0)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff8113bea0-ffffffff8113beb2: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811365b0)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff811365b0-ffffffff811365c2: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811373a0)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff811373a0-ffffffff811373b2: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff8115a050)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff8115a050-ffffffff8115a062: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81183980)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff81183980-ffffffff811839a4: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811beb50)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff811beb50-ffffffff811beb74: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811d1580)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff811d1580-ffffffff811d15a4: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff811e6200)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff811e6200-ffffffff811e6224: klp_shadow_get_or_alloc (STB_GLOBAL)
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
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (c0000000001f2320)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
c0000000001f2320-c0000000001f2338: klp_shadow_get_or_alloc (STB_GLOBAL)
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
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81125d00)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff81125d00-ffffffff81125d12: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81118760)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff81118760-ffffffff81118772: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81123bf0)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff81123bf0-ffffffff81123c02: klp_shadow_get_or_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *klp_shadow_get_or_alloc(void *obj, long unsigned int id, size_t size, gfp_t gfp_flags, klp_shadow_ctor_t ctor, void *ctor_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/shadow.c (ffffffff81130230)
Location: kernel/livepatch/shadow.c:225
Inline: False
```
**Symbols:**

```
ffffffff81130230-ffffffff81130242: klp_shadow_get_or_alloc (STB_GLOBAL)
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
