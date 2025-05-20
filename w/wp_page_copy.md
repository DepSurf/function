# Function: <code>wp_page_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811bc420)
Location: mm/memory.c:2060
Inline: True
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811bc420-ffffffff811bc965: wp_page_copy.isra.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wp_page_copy(struct fault_env *fe, pte_t orig_pte, struct page *old_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d7060)
Location: mm/memory.c:2138
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811d7060-ffffffff811d771b: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e6d10)
Location: mm/memory.c:2143
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811e6d10-ffffffff811e742d: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1f10)
Location: mm/memory.c:2349
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811f1f10-ffffffff811f2532: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208d80)
Location: mm/memory.c:2466
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81208d80-ffffffff812094fa: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81229c70)
Location: mm/memory.c:2508
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81229c70-ffffffff8122a3a0: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123d260)
Location: mm/memory.c:2244
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8123d260-ffffffff8123d9e4: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124ef00)
Location: mm/memory.c:2298
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8124ef00-ffffffff8124f6cf: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d4e0)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8125d4e0-ffffffff8125dc67: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128ce00)
Location: mm/memory.c:2651
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8128ce00-ffffffff8128d44a: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81297e00)
Location: mm/memory.c:2829
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81297e00-ffffffff81298426: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d4b0)
Location: mm/memory.c:2890
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8129d4b0-ffffffff8129da7d: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812ddbb0)
Location: mm/memory.c:2985
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812ddbb0-ffffffff812de11b: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133db60)
Location: mm/memory.c:3083
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8133db60-ffffffff8133e260: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b6c30)
Location: mm/memory.c:3063
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813b6c30-ffffffff813b739e: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eb5e0)
Location: mm/memory.c:3062
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813eb5e0-ffffffff813ebc07: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81416290)
Location: mm/memory.c:3117
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81416290-ffffffff814168b7: wp_page_copy (STB_LOCAL)
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
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f4b40)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffff8000102f4b40-ffff8000102f532c: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0516cf4)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0516cf4-c0517394: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bb7b0)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0000000003bb7b0-c0000000003bc300: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206022)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffe000206022-ffffffe0002065c8: wp_page_copy (STB_LOCAL)
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
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255b30)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81255b30-ffffffff812562b7: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81248210)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81248210-ffffffff81248947: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812538d0)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812538d0-ffffffff81254057: wp_page_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t wp_page_copy(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263290)
Location: mm/memory.c:2322
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81263290-ffffffff81263ae9: wp_page_copy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_fault *vmf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fault_env *fe</code>
</li>
<li>
<b>Param removed. </b>
<code>pte_t orig_pte</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *old_page</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
