# Function: <code>__probe_user_write</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff8122b180)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffffffff8122b180-ffffffff8122b237: __probe_user_write (STB_GLOBAL)
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
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffff8000102b97a0)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffff8000102b97a0-ffff8000102b99bc: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c04e5c5c)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
c04e5c5c-c04e5d40: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (c000000000371760)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
c000000000371760-c0000000003718cc: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffe0001dd0da)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffffffe0001dd0da-ffffffe0001dd15c: __probe_user_write (STB_GLOBAL)
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
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff812237d0)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffffffff812237d0-ffffffff81223887: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81216980)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffffffff81216980-ffffffff81216a37: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81221570)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffffffff81221570-ffffffff81221627: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __probe_user_write(void *dst, const void *src, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff81230730)
Location: mm/maccess.c:130
Inline: False
```
**Symbols:**

```
ffffffff81230730-ffffffff812307e7: __probe_user_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
