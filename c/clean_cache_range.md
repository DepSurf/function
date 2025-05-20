# Function: <code>clean_cache_range</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff818fd70c)
Location: arch/x86/lib/usercopy_64.c:88
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819851fc)
Location: arch/x86/lib/usercopy_64.c:88
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff819e15d5)
Location: arch/x86/lib/usercopy_64.c:108
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1c585)
Location: arch/x86/lib/usercopy_64.c:108
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a8c239)
Location: arch/x86/lib/usercopy_64.c:89
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ac34f9)
Location: arch/x86/lib/usercopy_64.c:89
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff815ff9b0)
Location: arch/x86/lib/usercopy_64.c:90
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff815ff9b0-ffffffff815ff9e4: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff816248e0)
Location: arch/x86/lib/usercopy_64.c:69
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff816248e0-ffffffff81624914: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff816082b0)
Location: arch/x86/lib/usercopy_64.c:69
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff816082b0-ffffffff816082e4: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81676ef0)
Location: arch/x86/lib/usercopy_64.c:69
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff81676ef0-ffffffff81676f24: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81791eb0)
Location: arch/x86/lib/usercopy_64.c:67
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff81791eb0-ffffffff81791ef2: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff8204fc80)
Location: arch/x86/lib/usercopy_64.c:27
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff8204fc80-ffffffff8204fcc2: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff820ce1d0)
Location: arch/x86/lib/usercopy_64.c:28
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff820ce1d0-ffffffff820ce212: clean_cache_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clean_cache_range(void *addr, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff821a89e0)
Location: arch/x86/lib/usercopy_64.c:28
Inline: False
Direct callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
**Symbols:**

```
ffffffff821a89e0-ffffffff821a8a22: clean_cache_range (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a62349)
Location: arch/x86/lib/usercopy_64.c:89
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81a1f3b9)
Location: arch/x86/lib/usercopy_64.c:89
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81ace739)
Location: arch/x86/lib/usercopy_64.c:89
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy_64.c (ffffffff81adac49)
Location: arch/x86/lib/usercopy_64.c:89
Inline: True
Inline callers:
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__memcpy_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:__copy_user_flushcache
  - arch/x86/lib/usercopy_64.c:arch_wb_cache_pmem
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
