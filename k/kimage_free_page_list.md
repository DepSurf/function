# Function: <code>kimage_free_page_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8110ccd0)
Location: kernel/kexec_core.c:311
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8110ccd0-ffffffff8110cd32: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81114600)
Location: kernel/kexec_core.c:334
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81114600-ffffffff8111466f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111bd20)
Location: kernel/kexec_core.c:334
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111bd20-ffffffff8111bd8f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8111da70)
Location: kernel/kexec_core.c:329
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8111da70-ffffffff8111dadf: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81129260)
Location: kernel/kexec_core.c:339
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff81129260-ffffffff811292cf: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811371b0)
Location: kernel/kexec_core.c:339
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811371b0-ffffffff8113721f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81142930)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81142930-ffffffff8114299f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114dc90)
Location: kernel/kexec_core.c:338
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8114dc90-ffffffff8114dcff: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811599a0)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811599a0-ffffffff81159a0f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116af3a)
Location: kernel/kexec_core.c:340
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8116ad70-ffffffff8116addf: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116767a)
Location: kernel/kexec_core.c:339
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811674b0-ffffffff8116751f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116840a)
Location: kernel/kexec_core.c:340
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81168240-ffffffff811682af: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118e14a)
Location: kernel/kexec_core.c:341
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8118df80-ffffffff8118dfef: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bd6aa)
Location: kernel/kexec_core.c:341
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811bd4a0-ffffffff811bd519: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811ff6ba)
Location: kernel/kexec_core.c:341
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811ff470-ffffffff811ff4e9: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81214ab6)
Location: kernel/kexec_core.c:342
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81214870-ffffffff812148e9: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122ca56)
Location: kernel/kexec_core.c:330
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_normal_control_pages
Direct callers:
  - kernel/kexec.c:kimage_alloc_init
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8122c810-ffffffff8122c889: kimage_free_page_list (STB_GLOBAL)
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
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffff8000101c9020)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000101c9020-ffff8000101c909c: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c040fee0)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
c040fee0-c040ff48: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c000000000231790)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c000000000231790-c000000000231850: kimage_free_page_list (STB_GLOBAL)
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
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81151fc0)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff81151fc0-ffffffff8115202f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811452a0)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff811452a0-ffffffff8114530f: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8114fe70)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8114fe70-ffffffff8114fedf: kimage_free_page_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kimage_free_page_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8115ccd0)
Location: kernel/kexec_core.c:340
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_free
  - kernel/kexec_core.c:kimage_alloc_control_pages
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:kimage_file_alloc_init
```
**Symbols:**

```
ffffffff8115ccd0-ffffffff8115cd3f: kimage_free_page_list (STB_GLOBAL)
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
