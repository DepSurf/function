# Function: <code>arch_static_call_transform</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff8103fda0)
Location: arch/x86/kernel/static_call.c:82
Inline: False
Direct callers:
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
```
**Symbols:**

```
ffffffff8103fda0-ffffffff8103fe2d: arch_static_call_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81041740)
Location: arch/x86/kernel/static_call.c:95
Inline: False
Direct callers:
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
```
**Symbols:**

```
ffffffff81041740-ffffffff810417cd: arch_static_call_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff810479e0)
Location: arch/x86/kernel/static_call.c:95
Inline: False
Direct callers:
  - kernel/static_call.c:__static_call_update
  - kernel/static_call.c:__static_call_update
```
**Symbols:**

```
ffffffff810479e0-ffffffff81047a6d: arch_static_call_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81050990)
Location: arch/x86/kernel/static_call.c:112
Inline: False
Direct callers:
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
```
**Symbols:**

```
ffffffff81050990-ffffffff81050a3a: arch_static_call_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff8105ddd0)
Location: arch/x86/kernel/static_call.c:157
Inline: False
Direct callers:
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
```
**Symbols:**

```
ffffffff8105ddd0-ffffffff8105de7a: arch_static_call_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff8105f470)
Location: arch/x86/kernel/static_call.c:157
Inline: False
Direct callers:
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
```
**Symbols:**

```
ffffffff8105f470-ffffffff8105f51a: arch_static_call_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_static_call_transform(void *site, void *tramp, void *func, bool tail);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/static_call.c (ffffffff81066520)
Location: arch/x86/kernel/static_call.c:157
Inline: False
Direct callers:
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_update
  - kernel/static_call_inline.c:__static_call_update
```
**Symbols:**

```
ffffffff81066520-ffffffff810665ca: arch_static_call_transform (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
