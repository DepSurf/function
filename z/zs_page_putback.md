# Function: <code>zs_page_putback</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122a380)
Location: mm/zsmalloc.c:2123
Inline: False
```
**Symbols:**

```
ffffffff8122a380-ffffffff8122a435: zs_page_putback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c8d0)
Location: mm/zsmalloc.c:2083
Inline: False
```
**Symbols:**

```
ffffffff8123c8d0-ffffffff8123c985: zs_page_putback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812485d0)
Location: mm/zsmalloc.c:2062
Inline: False
```
**Symbols:**

```
ffffffff812485d0-ffffffff81248685: zs_page_putback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812687a0)
Location: mm/zsmalloc.c:2076
Inline: False
```
**Symbols:**

```
ffffffff812687a0-ffffffff81268855: zs_page_putback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128d940)
Location: mm/zsmalloc.c:2079
Inline: False
```
**Symbols:**

```
ffffffff8128d940-ffffffff8128d9f5: zs_page_putback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a3140)
Location: mm/zsmalloc.c:2079
Inline: False
```
**Symbols:**

```
ffffffff812a3140-ffffffff812a31f5: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812be470)
Location: mm/zsmalloc.c:2098
Inline: False
```
**Symbols:**

```
ffffffff812be470-ffffffff812be55f: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d0360)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffffffff812d0360-ffffffff812d044f: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81306910)
Location: mm/zsmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffff81306910-ffffffff813069fc: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81312650)
Location: mm/zsmalloc.c:2051
Inline: False
```
**Symbols:**

```
ffffffff81312650-ffffffff8131273c: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81318b70)
Location: mm/zsmalloc.c:2048
Inline: False
```
**Symbols:**

```
ffffffff81318b70-ffffffff81318c5c: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2048
Inline: False
```
**Symbols:**

```
ffffffff81365120-ffffffff81365239: zs_page_putback (STB_LOCAL)
ffffffff81cc350b-ffffffff81cc351f: zs_page_putback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813dff60)
Location: mm/zsmalloc.c:1954
Inline: False
```
**Symbols:**

```
ffffffff813dff60-ffffffff813dffbd: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81466e50)
Location: mm/zsmalloc.c:2152
Inline: False
```
**Symbols:**

```
ffffffff81466e50-ffffffff81466ead: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149c370)
Location: mm/zsmalloc.c:1900
Inline: False
```
**Symbols:**

```
ffffffff8149c370-ffffffff8149c3d4: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cba90)
Location: mm/zsmalloc.c:1882
Inline: False
```
**Symbols:**

```
ffffffff814cba90-ffffffff814cbaf4: zs_page_putback (STB_LOCAL)
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
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff8000103751a0)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffff8000103751a0-ffff8000103752e4: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c056132c)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
c056132c-c0561438: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000467760)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
c000000000467760-c0000000004678e8: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024deca)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffffffe00024deca-ffffffe00024dffe: zs_page_putback (STB_LOCAL)
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
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c8940)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffffffff812c8940-ffffffff812c8a2f: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b9980)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffffffff812b9980-ffffffff812b9a6f: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c6750)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffffffff812c6750-ffffffff812c683f: zs_page_putback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zs_page_putback(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d7460)
Location: mm/zsmalloc.c:2100
Inline: False
```
**Symbols:**

```
ffffffff812d7460-ffffffff812d754d: zs_page_putback (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
