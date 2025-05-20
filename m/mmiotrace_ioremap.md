# Function: <code>mmiotrace_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81074450)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81074450-ffffffff810745ef: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81075a30)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81075a30-ffffffff81075bc2: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff810795d0)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810795d0-ffffffff81079762: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81077e80)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81077e80-ffffffff81078012: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff8107e1e0)
Location: arch/x86/mm/mmio-mod.c:280
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8107e1e0-ffffffff8107e372: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:279
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81081865-ffffffff81081876: mmiotrace_ioremap.cold.11 (STB_LOCAL)
ffffffff81081250-ffffffff810813d0: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:279
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81088475-ffffffff81088486: mmiotrace_ioremap.cold.12 (STB_LOCAL)
ffffffff81087e60-ffffffff81087fe0: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8108c0b5-ffffffff8108c0c6: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff8108bab0-ffffffff8108bc3a: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8108cd15-ffffffff8108cd26: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff8108c720-ffffffff8108c8aa: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81094030)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81094030-ffffffff8109409b: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81093580)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81093580-ffffffff810935eb: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:265
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81bcc19a-ffffffff81bcc1ab: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff81093cd0-ffffffff81093e63: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:265
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81ca2121-ffffffff81ca2146: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff810a3ab0-ffffffff810a3c4f: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:265
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81e51780-ffffffff81e517a6: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff810b8190-ffffffff810b833c: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:265
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff820552ab-ffffffff820552c0: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff810d39b0-ffffffff810d3b7d: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:265
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff820d387a-ffffffff820d388f: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff810d6d90-ffffffff810d6f5d: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:265
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff821ae6e8-ffffffff821ae6fd: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff810df5c0-ffffffff810df7bc: mmiotrace_ioremap (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8108bcd5-ffffffff8108bce6: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff8108b6e0-ffffffff8108b86a: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8107a813-ffffffff8107a824: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff8107a210-ffffffff8107a394: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8108bc85-ffffffff8108bc96: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff8108b690-ffffffff8108b81a: mmiotrace_ioremap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mmiotrace_ioremap(resource_size_t offset, long unsigned int size, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:267
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8108dfea-ffffffff8108dffb: mmiotrace_ioremap.cold (STB_LOCAL)
ffffffff8108d9f0-ffffffff8108db7d: mmiotrace_ioremap (STB_GLOBAL)
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
