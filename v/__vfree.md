# Function: <code>__vfree</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81269770)
Location: mm/vmalloc.c:2296
Inline: False
```
**Symbols:**

```
ffffffff81269770-ffffffff812697ca: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812786b0)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffffffff812786b0-ffffffff8127870a: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ac42f)
Location: mm/vmalloc.c:2349
Inline: True
Inline callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7520)
Location: mm/vmalloc.c:2330
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
```
**Symbols:**

```
ffffffff812b7520-ffffffff812b757d: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bcdf0)
Location: mm/vmalloc.c:2612
Inline: False
```
**Symbols:**

```
ffffffff812bcdf0-ffffffff812bce4d: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff560)
Location: mm/vmalloc.c:2665
Inline: False
Direct callers:
  - mm/vmalloc.c:vfree
```
**Symbols:**

```
ffffffff812ff560-ffffffff812ff5bd: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81366690)
Location: mm/vmalloc.c:2709
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
**Symbols:**

```
ffffffff81366690-ffffffff813666f9: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e22c0)
Location: mm/vmalloc.c:2771
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:vfree
```
**Symbols:**

```
ffffffff813e22c0-ffffffff813e2329: __vfree (STB_LOCAL)
```
</details>
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
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030efe8)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffff80001030efe8-ffff80001030f06c: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a838)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
c052a838-c052a8bc: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dfff0)
Location: mm/vmalloc.c:2302
Inline: False
Direct callers:
  - mm/vmalloc.c:vfree
```
**Symbols:**

```
c0000000003dfff0-c0000000003e0090: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe0002177b0)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffffffe0002177b0-ffffffe00021783a: __vfree (STB_LOCAL)
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
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270d00)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffffffff81270d00-ffffffff81270d5a: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262c70)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffffffff81262c70-ffffffff81262cca: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126eaa0)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffffffff8126eaa0-ffffffff8126eafa: __vfree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __vfree(const void *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e4a0)
Location: mm/vmalloc.c:2302
Inline: False
```
**Symbols:**

```
ffffffff8127e4a0-ffffffff8127e4fa: __vfree (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
