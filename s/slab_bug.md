# Function: <code>slab_bug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811e7450)
Location: mm/slub.c:591
Inline: False
Direct callers:
  - mm/slub.c:slab_err
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:check_object
  - mm/slub.c:on_freelist
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:free_debug_processing
```
**Symbols:**

```
ffffffff811e7450-ffffffff811e750c: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81206520)
Location: mm/slub.c:602
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff81206520-ffffffff812065dc: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81218540)
Location: mm/slub.c:599
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff81218540-ffffffff812185fc: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81224190)
Location: mm/slub.c:601
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff81224190-ffffffff81224245: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8123f7f0)
Location: mm/slub.c:636
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff8123f7f0-ffffffff8123f8a5: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8126a826)
Location: mm/slub.c:622
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8126a826-ffffffff8126a8e2: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127f0b6)
Location: mm/slub.c:627
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8127f0b6-ffffffff8127f172: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129af56)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff8129af56-ffffffff8129b012: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812aae16)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812aae16-ffffffff812aaed2: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812df6bb)
Location: mm/slub.c:654
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812df6bb-ffffffff812df777: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81be8e6a)
Location: mm/slub.c:649
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81be8e6a-ffffffff81be8f26: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81bdafc1)
Location: mm/slub.c:661
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81bdafc1-ffffffff81bdb07d: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81cc0b15)
Location: mm/slub.c:772
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81cc0b15-ffffffff81cc0bc2: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81e72f4b)
Location: mm/slub.c:819
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81e72f4b-ffffffff81e73016: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81423b30)
Location: mm/slub.c:883
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff81423b30-ffffffff81423bf9: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458e10)
Location: mm/slub.c:904
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff81458e10-ffffffff81458ed9: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81453dd0)
Location: mm/slub.c:1017
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:deactivate_slab
  - mm/slub.c:alloc_debug_processing
  - mm/slub.c:on_freelist
  - mm/slub.c:check_object
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
```
**Symbols:**

```
ffffffff81453dd0-ffffffff81453e99: slab_bug (STB_LOCAL)
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
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff80001034d3bc)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffff80001034d3bc-ffff80001034d480: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0550668)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
c0550668-c055071c: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c00000000042cc2c)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
c00000000042cc2c-c00000000042cd14: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023dadc)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffe00023dadc-ffffffe00023db70: slab_bug (STB_LOCAL)
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
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a33f6)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812a33f6-ffffffff812a34b2: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81294ec6)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff81294ec6-ffffffff81294f82: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a1206)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812a1206-ffffffff812a12c2: slab_bug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void slab_bug(struct kmem_cache *s, char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812b13b6)
Location: mm/slub.c:619
Inline: False
Direct callers:
  - mm/slub.c:check_bytes_and_report
  - mm/slub.c:slab_err
  - mm/slub.c:object_err
```
**Symbols:**

```
ffffffff812b13b6-ffffffff812b1472: slab_bug (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
