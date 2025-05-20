# Function: <code>finish_mkwrite_fault</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e8e60)
Location: mm/memory.c:2287
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - fs/dax.c:dax_pfn_mkwrite
```
**Symbols:**

```
ffffffff811e8e60-ffffffff811e8fb8: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f40c0)
Location: mm/memory.c:2493
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff811f40c0-ffffffff811f41f7: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120bda0)
Location: mm/memory.c:2614
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8120bda0-ffffffff8120bf0f: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122c960)
Location: mm/memory.c:2656
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8122c960-ffffffff8122cac8: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123feb0)
Location: mm/memory.c:2393
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8123feb0-ffffffff81240018: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81252000)
Location: mm/memory.c:2449
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81252000-ffffffff8125215f: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812605e0)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812605e0-ffffffff8126073f: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290bb0)
Location: mm/memory.c:2814
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
```
**Symbols:**

```
ffffffff81290bb0-ffffffff81290d0e: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129b640)
Location: mm/memory.c:2994
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:wp_page_shared
```
**Symbols:**

```
ffffffff8129b640-ffffffff8129b7a6: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0940)
Location: mm/memory.c:3055
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812a0940-ffffffff812a0a4c: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e1a30)
Location: mm/memory.c:3152
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812e1a30-ffffffff812e1b70: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81342830)
Location: mm/memory.c:3257
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81342830-ffffffff8134298d: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ba8a0)
Location: mm/memory.c:3240
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813ba8a0-ffffffff813ba9fd: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ef410)
Location: mm/memory.c:3241
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff813ef410-ffffffff813ef501: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf, struct folio *folio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81415570)
Location: mm/memory.c:3290
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81415570-ffffffff8141569a: finish_mkwrite_fault (STB_LOCAL)
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
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f7920)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffff8000102f7920-ffff8000102f7a98: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051a108)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c051a108-c051a26c: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c0780)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
c0000000003c0780-c0000000003c09dc: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000207eb2)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffe000207eb2-ffffffe000208018: finish_mkwrite_fault (STB_GLOBAL)
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
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81258c30)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81258c30-ffffffff81258d8f: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124b0f0)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff8124b0f0-ffffffff8124b23d: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812569d0)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff812569d0-ffffffff81256b2f: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
vm_fault_t finish_mkwrite_fault(struct vm_fault *vmf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81266440)
Location: mm/memory.c:2473
Inline: False
Direct callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
```
**Symbols:**

```
ffffffff81266440-ffffffff8126659b: finish_mkwrite_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
</ul>
</details>
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
