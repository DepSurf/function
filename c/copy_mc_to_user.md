# Function: <code>copy_mc_to_user</code>

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
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff81621770)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:copyout_mc
```
**Symbols:**

```
ffffffff81621770-ffffffff816217a6: copy_mc_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff81605070)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff81605070-ffffffff816050a6: copy_mc_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff81673960)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff81673960-ffffffff81673993: copy_mc_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff8178df40)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff8178df40-ffffffff8178dfbb: copy_mc_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff8204b770)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff8204b770-ffffffff8204b7eb: copy_mc_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff820ca050)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff820ca050-ffffffff820ca0d7: copy_mc_to_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int copy_mc_to_user(void *dst, const void *src, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/copy_mc.c (ffffffff821a49d0)
Location: arch/x86/lib/copy_mc.c:73
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_mc_to_iter
  - lib/iov_iter.c:_copy_mc_to_iter
```
**Symbols:**

```
ffffffff821a49d0-ffffffff821a4a33: copy_mc_to_user (STB_GLOBAL)
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
