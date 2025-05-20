# Function: <code>__online_page_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811ef960)
Location: mm/memory_hotplug.c:853
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff811ef960-ffffffff811ef97e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120ecb7)
Location: mm/memory_hotplug.c:930
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff8120ec80-ffffffff8120ec9e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81220ce7)
Location: mm/memory_hotplug.c:916
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81220cb0-ffffffff81220cce: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122c5f7)
Location: mm/memory_hotplug.c:669
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff8122c5c0-ffffffff8122c5de: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81247dd7)
Location: mm/memory_hotplug.c:678
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff81247da0-ffffffff81247dbe: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126b727)
Location: mm/memory_hotplug.c:654
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff8126b6f0-ffffffff8126b70e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8127ffb7)
Location: mm/memory_hotplug.c:655
Inline: True
Inline callers:
  - mm/memory_hotplug.c:generic_online_page
```
**Symbols:**

```
ffffffff8127ff80-ffffffff8127ff9e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129bfe0)
Location: mm/memory_hotplug.c:620
Inline: False
```
**Symbols:**

```
ffffffff8129bfe0-ffffffff8129bffe: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812abd50)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
ffffffff812abd50-ffffffff812abd6e: __online_page_free (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034ddf8)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
ffff80001034ddf8-ffff80001034de68: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042d320)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
c00000000042d320-c00000000042d374: __online_page_free (STB_GLOBAL)
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
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4330)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
ffffffff812a4330-ffffffff812a434e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81295e00)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
ffffffff81295e00-ffffffff81295e1e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a2140)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
ffffffff812a2140-ffffffff812a215e: __online_page_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __online_page_free(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b23d0)
Location: mm/memory_hotplug.c:595
Inline: False
```
**Symbols:**

```
ffffffff812b23d0-ffffffff812b23ee: __online_page_free (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
