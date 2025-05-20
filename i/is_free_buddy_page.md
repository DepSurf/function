# Function: <code>is_free_buddy_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81197da0)
Location: mm/page_alloc.c:6893
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81197da0-ffffffff81197e4d: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811acd00)
Location: mm/page_alloc.c:7441
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:shake_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811acd00-ffffffff811acdab: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bd260)
Location: mm/page_alloc.c:7494
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:shake_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811bd260-ffffffff811bd308: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c54c0)
Location: mm/page_alloc.c:7826
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811c54c0-ffffffff811c5568: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811da270)
Location: mm/page_alloc.c:7858
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811da270-ffffffff811da318: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811fab60)
Location: mm/page_alloc.c:8025
Inline: False
Direct callers:
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff811fab60-ffffffff811fac11: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120d2e0)
Location: mm/page_alloc.c:8357
Inline: False
Direct callers:
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff8120d2e0-ffffffff8120d391: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273740)
Location: mm/page_alloc.c:8573
Inline: False
Direct callers:
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81273740-ffffffff812737f4: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812825b0)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812825b0-ffffffff81282664: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b4730)
Location: mm/page_alloc.c:8738
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812b4730-ffffffff812b47dd: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c00c0)
Location: mm/page_alloc.c:8874
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812c00c0-ffffffff812c016d: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c5830)
Location: mm/page_alloc.c:9099
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812c5830-ffffffff812c58dd: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309f20)
Location: mm/page_alloc.c:9364
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81309f20-ffffffff81309ff0: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81368120)
Location: mm/page_alloc.c:9419
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81368120-ffffffff813681a3: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4180)
Location: mm/page_alloc.c:9584
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff813e4180-ffffffff813e4203: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81418ed0)
Location: mm/page_alloc.c:6491
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81418ed0-ffffffff81418f53: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81445a20)
Location: mm/page_alloc.c:6634
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81445a20-ffffffff81445aa3: is_free_buddy_page (STB_GLOBAL)
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
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff80001031aa70)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffff80001031aa70-ffff80001031aba8: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0534ff4)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
c0534ff4-c05350c4: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee270)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
c0000000003ee270-c0000000003ee3b0: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00022013e)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffe00022013e-ffffffe0002201dc: is_free_buddy_page (STB_GLOBAL)
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
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127ac00)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff8127ac00-ffffffff8127acb4: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126cae0)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff8126cae0-ffffffff8126cb94: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812789a0)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff812789a0-ffffffff81278a54: is_free_buddy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_free_buddy_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81288590)
Location: mm/page_alloc.c:8601
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
  - mm/memory-failure.c:memory_failure
  - fs/proc/page.c:stable_page_flags
```
**Symbols:**

```
ffffffff81288590-ffffffff81288644: is_free_buddy_page (STB_GLOBAL)
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
